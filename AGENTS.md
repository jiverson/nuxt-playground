
# Agent Instructions

This project is a Nuxt 4 application using Tailwind CSS.

## Build/Lint/Test Commands

- Build: `pnpm build`
- Lint: `pnpm lint` (fix: `pnpm lint:fix`)
- Dev: `pnpm dev` (runs db + Next.js with turbopack)
- No test framework configured


## General Guidelines
- **Simplicity First:** Write code as simple and readable as possible. Avoid unnecessary abstractions, over-engineering, or complex patterns.
- **Scope Discipline:** Only build features, components, and logic that are explicitly required by the project. Do not add extra functionality or files outside the described scope.
- **Consistency:** Follow the existing project structure and conventions. Place new files in the correct folders.

## Vue File Structure
- **Script First:** Always write `<script setup lang="ts">` blocks above `<template>` in Vue files.
- **TypeScript:** Use TypeScript for all scripts.
- **Minimal Logic:** Keep component logic minimal and focused on the component's purpose.

## Styling
- **Tailwind CSS:** Use Tailwind utility classes for styling. Do not use custom CSS unless necessary.
- **Custom Classes:** Do not add custom classes, always display the proper Tailwind classes in components.
- **Icon Usage:** Always import icon components (e.g., from `lucide-vue-next`) and use them directly in templates. Do not use icon font classes or <i> tags for icons.
- **shadcn-vue:** Use shadcn-vue UI components when possible. Prefer composition over custom UI unless required. Ask to execute command to add component when it is not present.

## Linting & Formatting
- **ESLint Compliance:** Ensure all code passes ESLint checks. Use the project's linting rules.
- **Formatting:** Follow the project's formatting conventions (indentation, spacing, etc.).

## Frontend Files Location
All frontend files are located in the `app` directory.

## Component Structure
- **File Naming:** Use kebab-case for component file names (e.g., `my-component.vue`).
- **Folder Structure:** Organize components by feature or domain, not by type.

## Component Usage
- **Reuse:** Prefer reusing existing components over creating new ones.
- **Location:** Place new components in the appropriate folder (e.g., `components/ui/`).

# Store Style Rule
Use the Pinia setup-style (composition API) store format for all new stores.

## Backend Files Location
All backend files are located in the `server` directory.

## Documentation
- **Comments:** Add comments only when necessary to explain non-obvious logic.
- **README:** Update documentation if you add or change major features.

## Do Not
- Do not add features, files, or logic outside the described requirements.
- Do not use libraries or dependencies not already present in the project.
- Do not change project configuration unless explicitly requested.

---

**Follow these rules to ensure code quality, maintainability, and project consistency.**

## Resources Used
- [Nuxt 4](https://nuxt.com/)
- [Vue 3](https://vuejs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
