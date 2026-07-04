# London Ravens Volleyball Club

A fully responsive, user-centric static website designed to provide an online presence for a local volleyball club. The platform is engineered to drive recruitment, streamline schedule updates, and act as a reliable contact point for supporters and opposing teams. 

## 🚀 Live Demo


## 📋 Academic Design Brief & Constraints
This project was developed as the final summative assessment for the "Web Design 1" university module. The development process was guided by a strict academic design brief, which required the following core constraints to be met:
* **Custom Codebase:** A strict requirement to use raw, hand-written HTML and CSS, without the use of third-party libraries, CSS frameworks (like Bootstrap), or code generators.
* **Site Architecture:** The site required a minimum of four interconnected pages (a front page linking to at least 3 sub-pages) with a consistent global layout.
* **Responsive Layouts:** Mandatory implementation of responsive CSS techniques, specifically utilizing modern tools like Flexbox.
* **External Integrations:** Required the successful embedding of at least one external service (achieved via the secure Google Maps iframe integration).
* **HCI & Accessibility:** A heavy grading emphasis on applying proper Human-Computer Interaction (HCI) principles, user-centric research, and adherence to Web Content Accessibility Guidelines (WCAG).

## 🎯 Project Overview
This project focuses on resolving Information Architecture challenges and managing technical trade-offs to deliver a seamless mobile-first experience. The UI utilizes a modern dark-mode aesthetic with vibrant green accents to convey an energetic and inclusive club identity while minimizing cognitive load.

## ✨ Key Features
* **Mobile-First Usability:** Fluid typography and a responsive CSS Grid/Flexbox structure ensure content is highly legible on small viewports.
* **Accessible Data Architecture:** Re-engineered traditional, rigid HTML schedule tables into vertically stacked Flexbox cards, prioritizing mobile scannability.
* **Screen Reader Support:** Implemented a strict, logical heading hierarchy (`<h3>` for match titles, `<p>` for dates) within the Flexbox cards to ensure screen readers can parse fixture data logically without relying on table headers.
* **Integrated Navigation:** A streamlined navigation bar and embedded Google Map reduce user cognitive load, allowing prospective players to find training locations instantly.
* **Privacy-First Analytics Tracking:** Designed to integrate with cookie-free, privacy-focused platforms (like Plausible) to track recruitment conversions while maintaining strict UK GDPR compliance.

## 🛠️ Built With
* **HTML5:** Semantic markup.
* **CSS3:** Flexbox, CSS Grid, Media Queries, and fluid typography. 
* **External Integrations:** Secure Google Maps `<iframe>` embed.

## 🧠 UX Insights & Technical Trade-Offs
During development, user testing revealed that displaying fixture data using standard semantic `<table>` elements resulted in inefficient horizontal scrolling on mobile devices. 

A calculated trade-off was made to abandon strict tabular semantics in favor of vertically stacked `<ul>` and `<li>` elements styled as Flexbox cards. This decision successfully resolved mobile UX friction while maintaining data accessibility. 

## 🛣️ Future Roadmap
As the club's requirements evolve, future iterations of this project will focus on:
1.  **Interactive Prototyping:** Utilizing Figma to create high-fidelity, interactive prototypes to simulate component states and touch targets prior to coding, allowing for more precise UI testing.
2.  **CSS Modularity:** Refactoring the current stylesheet using the Block Element Modifier (BEM) methodology to ensure components remain isolated, predictable, and scalable. 
3.  **Dynamic CMS Integration:** Using the BEM-structured components as a clean foundation to eventually migrate this static architecture into a dynamic WordPress environment, utilizing custom post types and PHP templates for easier roster and fixture management.
