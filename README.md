# Website Considerations

## Table of Contents
- [Development Process](#development-process)
- [Function](#function)
- [Content](#Content)
- [Usability & Accessibility](#usability--accessibility)
- [Aesthetics](#aesthetics)
- [Brand Adherence](#brand-adherence)
- [Client Agnosticism](#client-agnosticism)
- [Security](#security)
- [Infrastructure & Services](#infrastructure--services)
- [Maintainability & Scalability](#maintainability--scalability)
- [Content Management](#content-management)
- [Performance & Optimization](#performance--optimization)
- [Legal Protection](#legal-protection)
- [Social Media Integration](#social-media-integration)
- [SEO](#seo)
- [Localization](#localization)
- [Project-specific](#project-specific)
- [Quality Assurance](#quality-assurance)
- [Launch Strategy](#launch-strategy)
- [Analytics](#analytics)

---

## Development Process
- Goals need to be identified.
- Architecture needs to be set up (web hosting, build system, frameworks, etc.).
- Text content has to be written and all media assets have to be produced.
- Page elements have to be designed and then built.
- Data/content needs to be entered
- Finished work has to be tested and then deployed.
- Usage data has to be analyzed to determine effectiveness.
- Repeat.

## Function
- Website has clearly-defined core business, product, design, and technical goals
- Website achieves these goals
- The purpose of the website has been identified (e.g. is it primarily a brochure site? Blog? Web app? Is it driven by static content? User-generated content? Etc.)

## Content
- **Integrity**: Content is truthful, informative, and useful
- **Technicality**: Text content is spelled correctly and grammatically correct.
- **Quality**: Text content is concise and to the point, and shares a consistent voice. Image, video, and audio content is professionally-produced and serves its purpose
- **Information Architecture**: Well-structured, well-designed, user-focused content hierarchies and flows that anticipate users’ needs, attention spans, and successfully inform and help them navigate through the site

## Usability & Accessibility
- Good UX practices are used
- Views and navigation are intuitive
- UI leverages familiar paradigms
- Functional UI looks and feels smooth, solid, and snappy
- Error messages exist (and are useful) for likely edge cases
- Content is accessible to users who rely on assistive technologies like screen readers, closed captioning, keyboard-only input, and accessible color, contrast, and font size values
- WCAG/ADA compliant

## User Experience
- User is able to achieve their website interaction-related goals as efficiently and painlessly as possible
- User feels safe, confident, and well taken care of while they are interacting with the website
- User is delighted to interact with the website
- Fun stuff (budget-permitting), easter eggs, etc.

## Aesthetics
- Presentation is beautiful and professional
- Design is simple and clean, and good graphic design principles are employed (e.g. grids, color, typography, negative space, etc.)
- Subtle interactions and transition animations are used to enhance (but not overpower) the experience

## Brand Adherence
- Any existing brand, marketing, and design style guidelines are followed

## Client Agnosticism
- Website is agnostic to device, input method and browser
- Website is responsive and adapts to any screen size
- Website gracefully degrades on legacy browsers (e.g. some enhanced features are still usable in their more primitive renditions, use of polyfills where appropriate, display of error messages stating minimum supported browsers, etc.)
- no-JS fallback
- Determine if print stylesheet is warranted
- Determine if other device or media specific styles are warranted (e.g. reduced motion media queries)

## Security
- Sensitive data is protected
- System cannot be easily compromised
- System architecture lends itself to being more secure (e.g. SSG)
- Participants are using common sense when dealing with sensitive data
- Protection from bots spamming user forms (e.g. Captchas)

## Infrastructure & Services
- Domain is registered and DNS records are properly setup
- Web hosting is reliable, responsive, and well-optimized for the website running on it
- CDNs are used where appropriate
- Custom back-end services are working correctly, are secure, are optimized for their environments, and are able to handle the load of incoming requests
- Any integration with 3rd-party services or APIs is working properly with minimal downtime

## Maintainability & Scalability
- Website is built on a robust architecture
- All code is valid and standards-compliant
- Code best practices are used
- Views are data-centric and content can be managed easily without the risk of breaking the views
- Code is modular
- Code is versioned (e.g. via Git)
- Code is well-documented
- Architecture lends itself to scaling in the future
- Development, staging, and deployment architecture makes continuous integration easier

## Content Management
- CMS Infrastructure and UX
- Site data management
- User roles / permissions
- Asset management

## Performance & Optimization
- Website load times are minimal
- Front-end code is as lightweight as possible (elegantly written with no unnecessary libraries or frameworks and no memory leaks)
- Image assets are optimized and/or compressed
- Decreased reliance on real-time services for rendering content
- Use of CDN hosting where appropriate
- Use of code minification where appropriate
- Performance analysis tools are used to fine-tune the experience

## Legal Protection
- Content creators have granted permission for usage of all content
- Usage of any 3rd-party code libraries, fonts, media assets, etc. is compatible with their respective licenses
- GDPR and CCPA compliance
- Content is not defamatory against any group or individual and does not infringe on anyone’s rights
- Material complies with local law
- Copyright info, Terms & Conditions and Privacy Policy pages exist (with prominent links on every page) where appropriate, and GDPR is addressed where appropriate

## Social Media Integration
- Website is configured to be easily shared on popular social media platforms (e.g. contains appropriate Open Graph and Twitter meta tags)
- Website promotes its own social media channels

## SEO
- There is at least an awareness of SEO considerations when developing custom content
- Markup leverages appropriate semantics
- View layers contain helpful metadata for search crawlers
- View layers are formatted to be most SEO-friendly (e.g. how CSS is rendered)
- View layers do not use any tricks that might penalize search rankings
- Analysis tools like Google Search Console are used to identify any SEO issues
- Sitemap has been created and registered with Google

## Localization
- TODO: Add points for localization

## Project-specific
- Any project-specific goals or considerations that are beyond the scope of this doc.

## Quality Assurance
- Website has been thoroughly tested and has been determined to have achieved the above goals
- Any bugs that are uncovered are tracked, triaged, and fixed
- Content has been spell-checked and typos have been addressed

## Launch Strategy
- TODO: Add points for launch strategy

## Analytics
- Data is being collected on how users are interacting with the website (e.g. Google Analytics or a custom solution)
- Data is being analyzed to fine-tune website execution in order to further high-level goals
