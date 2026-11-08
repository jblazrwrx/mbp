Photography Business Website — Project Instructions

1. Project Objective

Develop a lightweight, professional, responsive static website for a photography business.

The website's primary purpose is to establish business credibility, communicate photography services, introduce the photographer, and generate prospective customer inquiries.

This is a business website, not a comprehensive photography portfolio or gallery platform.

Prioritize:

Professional presentation

Strong visual design

Fast loading

Mobile responsiveness

Clear service descriptions

Search engine visibility

Simple navigation

Clear contact and inquiry pathways

Easy future maintenance

Avoid unnecessary complexity.

2. Project Structure

The current workspace directory is the Git repository root.

All website application code must reside inside:

/website/

Do not place application source code, dependencies, build output, or website configuration files in the repository root unless explicitly requested.

Repository-level documentation and development instructions may reside outside /website/.

3. Technology Stack

Use Astro as the static site framework.

Requirements:

Astro with static output.

HTML and CSS for presentation.

Minimal vanilla JavaScript when necessary.

No React, Vue, Svelte, or other frontend frameworks.

No backend or server-side application.

No database.

No CMS.

No unnecessary dependencies or third-party libraries.

Use semantic HTML and accessible components.

The website should be statically generated and deployable to a conventional static hosting provider.

4. Website Pages

The initial website should contain:

Homepage

Services

About

Contact

The homepage should serve as the primary landing page and direct visitors toward services and contact information.

Do not build an extensive gallery. Use a limited number of carefully selected photographs to establish the photographer's style and capabilities.

Keep the architecture flexible enough to add pages later.

5. Design Direction

The design should feel contemporary, polished, professional, and photography-oriented.

Prioritize:

Large, impactful photography

Thoughtful typography

Generous whitespace

Clear visual hierarchy

Restrained animations

Consistent spacing

Strong mobile layouts

Intuitive navigation

Avoid:

Generic website templates

Excessive gradients

Unnecessary animations

Overly complicated layouts

Excessive card-based design

Decorative elements that compete with photography

Stock photography presented as actual business work

Use temporary image placeholders where actual business photography has not yet been provided.

Do not invent business credentials, customer testimonials, awards, locations, pricing, or services.

6. Components and Styling

Use reusable Astro components for elements that appear across multiple pages.

At minimum:

Header/navigation

Footer

Contact CTA

Base page layout

Keep global styles in a centralized stylesheet.

Avoid duplicating CSS and markup unnecessarily.

Use responsive CSS and prioritize mobile usability.

7. Content and SEO

Each page must have:

An appropriate page title

A unique meta description

Semantic heading structure

Appropriate image alt text

Implement:

Open Graph metadata

Favicon

Canonical URLs when the production domain is known

Sitemap generation when appropriate

Robots.txt

Do not invent business information to fill content gaps. Use clearly identifiable placeholders.

8. Contact Functionality

The contact page must provide an obvious way to inquire about services.

Initially, prefer a simple email-based contact mechanism unless a functional form provider is explicitly approved.

Do not create a form that appears functional but does not actually submit information.

Do not introduce a backend.

9. Development Workflow

Work incrementally.

Before making substantial changes:

Inspect the existing workspace.

Confirm the intended project structure.

Explain the proposed implementation.

Identify any missing business information or assets.

Do not overwrite or delete existing user files without approval.

When implementing:

Make focused changes.

Avoid unnecessary dependencies.

Explain important architectural decisions.

Keep the code readable and maintainable.

Do not introduce features outside the project scope.

Do not deploy, purchase services, modify DNS, or change external accounts without explicit approval.

10. Quality Assurance

Before considering the website complete:

Run the production build.

Resolve build errors and warnings where practical.

Check all internal navigation.

Check mobile and desktop layouts.

Verify images load correctly.

Verify contact links.

Check page titles and metadata.

Check accessibility basics.

Check for broken links and missing assets.

Do not claim something has been tested unless it has actually been tested.

11. Deployment

Prepare the website for deployment to a static hosting provider.

Preferred initial deployment candidate: Cloudflare Pages.

Keep deployment configuration straightforward.

The production build should generate a static dist/ directory inside /website/.

Do not deploy until explicitly authorized.

12. Working With the User

The user is comfortable working in VS Code and GitHub and understands basic software development concepts.

Be direct and avoid unnecessary explanations.

Do not overengineer.

When multiple implementation approaches are available, explain the tradeoffs and recommend one.

Ask questions when business information or design decisions materially affect implementation. Do not invent answers.

Prioritize a successful, maintainable launch over adding features.