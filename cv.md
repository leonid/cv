# CV -- Leonid Romanov

**Location:** Sofia, Bulgaria
**Email:** romanov.leonid@gmail.com
**LinkedIn:** [linkedin.com/in/leonid-romanov](https://www.linkedin.com/in/leonid-romanov/)
**Portfolio:** github.com/leonid/cv
**GitHub:** github.com/leonid

## Professional Summary

Frontend engineer and tech lead with 20+ years in web development, focused on design systems, frontend platforms and complex, data-dense interfaces.
Founded and owned the open-source Acronis UI kit, used across all Acronis product consoles through React, Vue 2, Vue 3 and back to React; designed the OpenAPI contract between frontend and backend at Virtuozzo; and built the first micro-frontend architecture for the new Acronis Cyber Console.
Works as both developer and designer, from Figma libraries and design tokens to AI design-to-code workflows with Figma Code Connect and Claude Code. Earlier built the frontend and mobile apps of the AVITO.ru classifieds platform from the ground up.

## Work Experience

### Acronis -- Sofia, Bulgaria

**Lead Software Engineer**
Feb 2020 – Sep 2026

- Tech lead of the central frontend platform team (~8 engineers), working with 3–4 frontend product teams on the Management Console, Backup Console, Cyber Infrastructure console, and, from 2025, the new Cyber Console.
- Interviewed frontend candidates, mentored developers, and acted as a main code reviewer across many frontend projects.
- Founded and owned the Acronis UI kit, used across all product consoles. Evolved it through React, Vue 2 and Vue 3, then back to React for the new Cyber Console. It covers the full component set, icons, fonts and design tokens. Published as open source ([acronis/uikit](https://github.com/acronis/uikit), [acronis/ui-component-library](https://github.com/acronis/ui-component-library)) and shared by Acronis, Virtuozzo and Constructor.
- Maintained the company-wide Figma library and the kit's delivery pipeline: Git repositories, Jenkins CI, and build/release workflows.
- Standardized Figma file structure, naming and linting rules so AI tooling could process designs reliably.
- Built an AI design-to-code workflow that generates React components from the design system. It combines Figma Code Connect (with the Figma MCP server for local development), a design grammar (rules for how components look, behave and interact) and custom skills for specialized agent roles.
- Designed the first micro-frontend architecture for the new Cyber Console. Built several proofs of concept with Vite and Module Federation (vite-plugin-federation), leading to an MVP that combined modules from the existing consoles into one new console. Started as a Vite monorepo with a generic shell, then split into per-micro-frontend repositories with their own Jenkins CI and build pipelines.
- Added Module Federation support to the UI kit and published a web-components build of its components.
- Created table components for data-dense workflows with up to 20,000–30,000 rows, supporting both server-side windowing (item-ID cursor with sorting and filtering on the backend API) and client-side virtualization; some product teams offloaded processing to Web Workers to keep page load responsive.
- Introduced AI-assisted engineering workflows using Claude and Codex, integrating GitHub, Jira, Confluence, Bitbucket, Docker, and Jenkins; used GitHub Actions for open-source projects.
- Co-created a custom AI orchestration system that generated product-manager specifications and developer specifications for microfrontend areas of a new Cyber Console, supporting 3–4 teams of 5–7 people each.

### Virtuozzo

**Senior Software Engineer**
Aug 2016 – Feb 2020

- Drove frontend architecture for Virtuozzo Hybrid Infrastructure (VHI) as the team grew from 2–3 to 5–6 frontend developers, taking it from a legacy XSL/jQuery interface through a full rewrite to React and then Vue 2. The same frontend also shipped as Acronis Cyber Infrastructure (ACI), built at Virtuozzo for Acronis.
- Designed the backend-for-frontend (BFF) principles and an OpenAPI/Swagger contract between frontend and backend, covering REST and async (WebSocket) API schemas. Backend endpoints were then brought in line with the Swagger schemas, with validation rules on both sides using IBM OpenAPI Validator.
- Used OpenAPI Generator to produce a Node.js fake backend, Python code and TypeScript types from the YAML specifications; the fake backend powered end-to-end and functional tests in TestCafe.
- Built Chromatic-style visual regression testing running in Docker, extended with Storybook stories, e2e scenarios and snapshot tests covering all visual components; added accessibility checks with axe.
- Created a UI system and a Vue 2 UI kit with interface standards for admin panels (sidebar navigation, data tables, detail views); data tables were fully standardized on the backend WebSocket API.
- Acted as the product's developer-designer, producing UI design in Photoshop, then Sketch, then Figma.

### ProtonPlusService

**Senior Frontend Developer**
Jun 2015 – Jul 2016

- Built the frontend of a real-time tactical border-monitoring application for a government border agency: a live Leaflet map tracking vehicles, aircraft, vessels and border-control devices, with operator alerts.
- Implemented real-time data feeds over WebSockets, server-sent events and polling, depending on the device type.
- Migrated the UI from AngularJS to Vue.js, as one of 3 UI developers working with 3 QA engineers and 6–7 Java backend developers.

### MyJet
**Senior Frontend Developer**
May 2014 – Nov 2014

- Built frontend features for a commercial application that private-jet owners and operating companies used to manage flights, aircraft maintenance and operating budgets, on a Django-based product.

### AVITO.ru

**Lead Frontend Developer**
Dec 2009 – Apr 2014

- Built the frontend of a high-traffic classifieds platform from the ground up, using JavaScript and jQuery initially, with PHP/Twig integration, and optimized the experience for heavy traffic.
- Delivered desktop and mobile web experiences, including lightweight versions for WAP browsers during the transition from feature phones to early smartphones.
- Built a Java ME (J2ME) application for feature phones, then independently developed mobile applications for iOS and Android (around 2012–2013), using HTML/CSS/JavaScript in WebView-based implementations where appropriate, and built the supporting REST APIs in PHP.
- Created localized marketplace products for Morocco (avito.ma) and Egypt (bekam.com), transferring core product functionality to Arabic-speaking markets and coordinating with local developers and translators; worked with Arabic and French content.
- Developed a Redis-backed statistics service and experimented with Tarantool for performance-sensitive data workflows.
- Built internal tools for listing moderation and customer support, plus an A/B testing system for evaluating new features.
- Worked with data-center contractors in Sweden on infrastructure requirements, equipment selection, site visits, and infrastructure acceptance for a high-load project.
- Following mobile product launches, traffic reportedly reached hundreds of thousands to around one million unique users; mobile applications helped drive views and advertising sales, with investment reportedly recovered within about a week.

### Webalta
**Frontend Web Developer**
Jan 2009 – Dec 2009
Built web interfaces for a search-engine portal using Java and Apache Wicket.

### JSC Publishing House Salon-Press

**Frontend Developer**
Sep 2007 – Sep 2009

- Delivered digital editions, websites, and web applications for publishing and events.

### ADV/web-engineering co.

**Web Developer**
Sep 2006 – Sep 2007

- Built custom web applications using Java, XML/XSL, and reusable web components.
- Worked with Panasonic, and other clients; CMS integration and publishing platforms; e-commerce and enterprise IT support.

### OTR-2000

**Technical Support Specialist**
Sep 2005 – Sep 2006

- Deployed and supported an automated information system for a Ministry of Finance and Treasury environment.

### BRUTTO

**Web Developer**
Dec 2004 – Sep 2005

- Delivered 50+ custom websites, CMS integration, HTML/CSS, and cross-browser compatibility
- Volkswagen dealer websites, including multilingual content and localized product information

### PromInvest, LLC

**Web Developer**
Jan 2004 – Dec 2004

- Built e-commerce and single-brand web platforms for mobile and consumer-electronics retail.

### PC Help

**IT Support Specialist**
Jun 2003 – Jan 2004

- Provided onsite business IT support, workstation configuration, and troubleshooting.

## Projects

- **Acronis UI Kit** (Open Source) -- React component library with components, icons, fonts and design tokens, used across Acronis product consoles and shared with Virtuozzo and Constructor. [github.com/acronis/uikit](https://github.com/acronis/uikit) · [github.com/acronis/ui-component-library](https://github.com/acronis/ui-component-library)
- **Electric** (side project, private beta) -- SaaS for freelance electricians, electrical designers and small contractors in Europe, starting in Bulgaria, that turns a floor plan into a professional low-voltage electrical project; now being tested on real apartment projects. React 19 / TypeScript / Vite monorepo with the engineering domain split into framework-independent packages (calculations, validation rules, distribution board, BOM, documents). Deterministic load, voltage-drop and cable-capacity calculations with rule-based validation. Node.js API with PostgreSQL, PDF output and i18n. Covered by Vitest and Playwright tests with axe accessibility checks; deployed with Docker. Built solo, with Claude Code as the primary implementation tool under my architecture and review.

## Education

- Higher education in Applied Mathematics;
- additional higher education in Sociology.

## Skills

- **Frontend:** React, Next.js, Vue 2/3, AngularJS, TypeScript, JavaScript, HTML, CSS, jQuery, ExtJS
- **State & Data Fetching:** Redux, Zustand, MobX, Vuex, Pinia, TanStack Query
- **Styling:** CSS Modules, SCSS, Stylus, Tailwind CSS, CSS-in-JS
- **Design Systems:** Figma, Figma Code Connect, Figma MCP, Storybook, design tokens, Style Dictionary, Tokens Studio, Radix UI, shadcn/ui, Element, Vuetify, Ant Design, Sketch, Photoshop
- **Frontend Architecture:** Microfrontends, Module Federation, Web Components, monorepos, backend-for-frontend (BFF), component libraries
- **Build Tools:** Vite, Webpack, Rollup, esbuild
- **APIs & Real-time:** OpenAPI/Swagger, OpenAPI Generator, IBM OpenAPI Validator, REST, WebSockets, server-sent events, WebRTC, GraphQL (limited)
- **Browser Platform & Visualization:** Web Workers, PWA / Service Workers, Electron, D3, Three.js, Leaflet
- **Performance & Accessibility:** Lighthouse, caching strategies, lazy loading, code splitting, WCAG audits, axe
- **Testing & CI/CD:** Jest, Vitest, Cypress, Playwright, TestCafe, visual regression testing, snapshot testing, Jenkins, GitHub Actions
- **Backend & Data:** Node.js (Express, Fastify), PHP, PostgreSQL, MySQL, MongoDB, Redis, Tarantool (experimental)
- **Infra & Observability:** Docker, Kubernetes, Nginx, Grafana, Prometheus
- **Languages:** TypeScript, JavaScript, SQL, PHP, Python, Bash, Java (earlier work)
- **AI-assisted Development:** Claude Code, Codex, Figma MCP, AI design-to-code workflows, agent skills and roles, AI-generated product and developer specifications
- **Domains:** Enterprise cybersecurity and infrastructure consoles, data-dense admin UIs, high-traffic marketplaces, localization (Arabic, French), internal tools (moderation, support), A/B testing
- **Mobile:** WebView-based iOS and Android apps, Java ME (J2ME)

## Courses

- Design and accessibility courses (during AVITO.ru)
- Web development and SEO courses (during ADV/web-engineering)

## ADDITIONAL EXPERIENCE

- Earlier experience includes frontend and web development with Java, Apache Wicket, XML/XSL, CMS integrations, publishing platforms, e-commerce, and enterprise IT support.

## Languages

- English — B1–B2 working proficiency
- Russian — Native
- Bulgarian — B2–C1
