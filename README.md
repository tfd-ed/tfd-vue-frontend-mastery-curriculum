# Frontend Development Mastery (30 hours)
**VueJS + TailwindCSS - Building reactive applications**

## Objective
This curriculum is designed to take you from a beginner to a proficient Vue.js developer. You will learn the fundamentals of reactive UI development, build complex single-page applications, and master state management and modern tooling.

## Outcome
Upon completion, you will be able to:
*   Build and deploy reactive web applications with Vue.js and TailwindCSS.
*   Structure applications using components, routing, and state management.
*   Integrate with APIs and handle asynchronous operations.
*   Write reusable and maintainable code with composables.
*   Implement advanced features like internationalization.

---

## Vue.js Fundamentals (7.5 hours)

**Day 1 (Monday) - Introduction to Vue.js & Setup** | 1.5 hours
- Theory (45 min): What is Vue.js, reactive frameworks comparison, Vue vs React/Angular, CDN vs CLI setup
- Practice (45 min): Create first Vue app, basic data binding, understand Vue instance

**Day 2 (Tuesday) - Template Syntax & Directives** | 1.5 hours
- Theory (40 min): Interpolation, v-bind, v-on, v-if/v-show, v-for, event handling
- Practice (50 min): Build interactive list with conditional rendering and event handlers

**Day 3 (Wednesday) - Data Binding & Forms** | 1.5 hours
- Theory (45 min): v-model, two-way binding, form input types, modifiers (.lazy, .number, .trim)
- Practice (45 min): Create form with validation, handle user input, dynamic styling

**Day 4 (Thursday) - Methods & Computed Properties** | 1.5 hours
- Theory (40 min): Methods vs computed vs watchers, reactivity system, data flow
- Practice (50 min): Build calculator with computed properties, shopping cart with watchers

**Day 5 (Friday) - Components Basics** | 1.5 hours
- Theory (40 min): Component concept, props, events, component registration
- Practice (50 min): Create reusable card component, build todo app with components

---

#### Components & Communication (7.5 hours)

**Day 1 (Monday) - Props & Component Communication** | 1.5 hours
- Theory (40 min): Props passing, prop validation, prop types, parent-to-child communication
- Practice (50 min): Build nested component structure with data flow

**Day 2 (Tuesday) - Custom Events & Emits** | 1.5 hours
- Theory (45 min): Emitting custom events, child-to-parent communication, event modifiers
- Practice (45 min): Create interactive components that communicate (e.g., product list with cart)

**Day 3 (Wednesday) - Slots & Component Composition** | 1.5 hours
- Theory (40 min): Default slots, named slots, scoped slots, slot props
- Practice (50 min): Build reusable layout components (Card, Modal, Tabs)

**Day 4 (Thursday) - Component Lifecycle Hooks** | 1.5 hours
- Theory (45 min): Component lifecycle, mounted/created/updated/unmounted, watchers, use cases
- Practice (45 min): Fetch data on mount, cleanup on unmount, track component state

**Day 5 (Friday) - Integration Workshop** | 1.5 hours
- Workshop (75 min): Hands-on integration of all Week 3-4 concepts (props, events, slots, lifecycle hooks)
- Build a complete Movie Review Application combining all learned component patterns

---

#### Vue Router & State Management (7.5 hours)

> **⚠️ IMPORTANT**: Before starting Week 5, you **must** install Node.js on your computer. Week 5 transitions from CDN-based development to using build tools (Vite) and proper project structure.

**Day 1 (Monday) - Vue CLI & Router Setup** | 1.5 hours
- Theory (45 min): SPA concept, npm create vue, project structure, Vue Router basics, Single File Components
- Practice (45 min): Set up Vue project with Router, create Home/About/Contact pages

**Day 2 (Tuesday) - Dynamic Routes & Parameters** | 1.5 hours
- Theory (40 min): Route params, query parameters, programmatic navigation, route guards
- Practice (50 min): Build product detail pages, user profiles with dynamic routes

**Day 3 (Wednesday) - Nested Routes & Navigation Guards** | 1.5 hours
- Theory (45 min): Nested routing, route meta fields, beforeEach, beforeEnter guards
- Practice (45 min): Create nested layout with sidebar navigation, protected routes

**Day 4 (Thursday) - Introduction to Pinia** | 1.5 hours
- Theory (40 min): State management concept, Pinia vs Vuex, stores, state, getters, actions
- Practice (50 min): Create global store for user data, shopping cart, or app settings

**Day 5 (Friday) - Pinia in Practice** | 1.5 hours
- Theory (30 min): Multiple stores, store composition, persisting state
- Practice (60 min): Integrate Pinia into existing app, manage complex state

---

#### Advanced Features & Deployment (7.5 hours)

**Day 1 (Monday) - API Integration & Async Operations** | 1.5 hours
- Theory (40 min): Fetch API, axios, async/await, loading states, error handling
- Practice (50 min): Build app that fetches data from public API (weather, movies, etc.)

**Day 2 (Tuesday) - Composables & Reusable Logic** | 1.5 hours
- Theory (45 min): Composition API basics, reusable composables, useRouter, custom composables
- Practice (45 min): Create useFetch, useLocalStorage, useToggle composables

**Day 3 (Wednesday) - Internationalization (i18n)** | 1.5 hours
- Theory (40 min): vue-i18n setup, translation files, language switching, pluralization
- Practice (50 min): Add multi-language support to app (English, Khmer, etc.)

**Day 4 (Thursday) - Styling & Fonts** | 1.5 hours
- Theory (30 min): TailwindCSS with Vue, scoped styles, Google Fonts, custom fonts
- Practice (60 min): Style complete app with TailwindCSS, add custom typography

**Day 5 (Friday) - Deployment with Netlify** | 1.5 hours
- Theory (30 min): Build process, environment variables, Netlify setup, CI/CD basics
- Practice (60 min): Deploy Vue app to Netlify, configure custom domain, test production

**🎯 End of Module Project: Full-Stack SPA Application**