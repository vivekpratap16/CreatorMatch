🚀 CreatorMatch: The Ultimate Creator-Brand Marketplace

📖 1. Project Summary

CreatorMatch is a fully responsive, two-sided web-based marketplace designed to bridge the gap between Content Creators and Global Brands. Built with a modern tech stack, it allows brands to discover top talent, view dynamic portfolios (including YouTube showcases and social stats), and send real-time collaboration pitches that trigger instant email notifications.

💡 2. The Business Idea & Problem it Solves

The Problem: Currently, brands struggle to find niche-specific creators. They rely on manual Instagram/YouTube searches or expensive PR agencies. On the flip side, emerging creators struggle to get discovered by legitimate brands.
The Solution (CreatorMatch): A centralized hub where:

Creators can build a "Premium Portfolio" showcasing their niche, follower count, bio, and a featured video.

Brands/Businesses can easily filter creators by category and send collaboration requests directly through the platform.

Monetization Potential (Future Scope):

Freemium Model: Basic search is free; advanced filters require a brand subscription.

Commission Model: Taking a small percentage of the deal closed through the platform.

Featured Profiles: Creators can pay a small fee to rank higher in brand search results.

✨ 3. Key Features

Dual-Role Architecture: Role-based authentication (Creator vs Business). The dashboard dynamically adapts based on who logs in.

Premium UI/UX: Built with Tailwind CSS featuring modern Glassmorphism, animated backgrounds, hover effects, and responsive design for mobile and desktop.

Dynamic Profile Pages: Auto-generated profiles using URL parameters (?id=...). Profiles feature YouTube video embeds, social media links, and interactive buttons.

Real-Time Search & Filters: Brands can instantly search creators by name or filter by niche without page reloads.

Smart Request System: Brands can pitch to creators with a click. Creators have a dedicated inbox to "Accept" or "Pass" on requests.

Automated Email Notifications: Integrated EmailJS to send actual emails to creators the moment a brand pitches them, completely serverless.

Guest Mode: Unauthenticated users can explore the platform in a restricted 'read-only' mode to see platform value before signing up.

🛠️ 4. Tech Stack Used

Frontend: HTML5, CSS3, JavaScript (ES6 Modules)

Styling: Tailwind CSS (via CDN)

Backend & Database: Google Firebase (Cloud Firestore NoSQL)

Authentication: Firebase Auth (Email & Password)

Third-Party API: EmailJS (for serverless email dispatch)

Design Language: Plus Jakarta Sans font, Glassmorphism, CSS Keyframe Animations.
