# SCSS Base Setup

This repository provides a foundational SCSS (Sass) architecture for scalable and maintainable front-end projects. It includes a structured set of folders and files for organizing design tokens, themes, layout rules, and vendor styles. The goal is to help teams quickly bootstrap new projects with a clear separation of concerns, reusable patterns, and best practices for writing modular and consistent SCSS code.

---

> **Note:** This SCSS architecture was created with reference and inspiration from [Sass Guidelines by Hugo Giraudel](https://sass-guidelin.es/#architecture). The structure and best practices outlined here are heavily influenced by the recommendations in that resource.

---

## Benefits of This SCSS Architecture

The following are some of the key benefits you'll gain by using this SCSS base setup:

- 🚀 **Faster Project Setup:** Quickly start new projects with a ready-to-use SCSS structure.
- 🧩 **Modular Codebase:** Organize styles into clear, reusable modules for easy maintenance.
- 🛠️ **Easy Customization:** Effortlessly adapt themes, tokens, and layouts to project needs.
- 🧹 **Consistent Styling:** Enforce design consistency across all components and pages.
- 👥 **Team Friendly:** Simplifies collaboration with clear folder and file conventions.
- 📦 **Scalable Architecture:** Supports growth from small to large projects without chaos.
- 📚 **Best Practices:** Encourages clean, maintainable, and future-proof SCSS code.


## How to Use This Repo

Clone or download this repository, and then place the folder into your project's working directory.


### Folder & File Structure Overview (Alphabetical Order)

- **abstracts/**  
  Stores global settings, functions, mixins, and helpers for the project.
  - `_functions.scss`: Defines global SCSS functions for calculations and value manipulations.
  - `_mixins.scss`: Contains reusable mixins to avoid code repetition and add logic to styles.
  - `_placeholders.scss`: Stores placeholder selectors (`%`) for extending common style patterns.
  - `_variables.scss`: Declares global variables (z-index, breakpoints) used throughout the project.
  - `index.scss`: Centralizes and exposes all abstract utilities for easy import.

- **base/**  
  Contains base styles like resets, typography, and HTML element rules.  
  - `_global.scss`: Defines global styles (like styling body, a etc to match the design system) applied across the project, beyond the CSS reset.
  - `_reset.scss`: Applies a modern CSS reset for consistent default styling and cross-browser normalization.
  - `index.scss`: Aggregates all base styles for consistent project-wide defaults.

- **components/**  
  Holds reusable UI components such as buttons, cards, and forms.  
  - `index.scss`: Collects and exports all component styles for modular usage.

- **layout/**  
  Manages layout-related styles for structure and positioning.  
  - `_default.scss`: Defines global, reusable layout styles for the whole project.  
  - `_page.scss`: Adds layout styles unique to individual pages.
  - `index.scss`: Aggregates and exposes all layout styles for easy import.

- **themes/**  
  Contains theme-specific styles (e.g., dark/light mode, color schemes).  
  - `index.scss`: Gathers and exposes all theme files for easy import.

- **tokens/**  
  Stores design tokens like colors, spacing, and typography scales.  
  - `_colors.scss`: Has all the color tokens from the design system here.
  - `index.scss`: Centralizes and exports all token files for consistent usage.

- **vendors/**  
  Includes third-party or external SCSS/CSS libraries.  
  - `index.scss`: Imports and manages all vendor styles in one place.





