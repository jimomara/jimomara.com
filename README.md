# jimomara.com
My personal website

## Code Structure
my-website/
├── public/                   # Static assets (images, favicon, etc.)
│   ├── Matt Bernier_Resume.pdf
    ├── file.svg
    ├── globe.svg
    ├── matt.hat.jpg
    ├── next.svg
    ├── vercel.svg
    └── window.svg
├── src/
│   ├── components/           # Reusable UI components
│   │   ├── Header.tsx        # Navigation bar component
│   │   ├── Footer.tsx        # Footer component
│   │   ├── Layout.tsx        # Layout wrapper component
│   │   └── ...               # Other UI components
│   ├── app/                # Next.js pages
        │   │   ├── articles
        │   ├── [slug]
        │   │   └── page.tsx
        │   └── page.tsx
        ├── favicon.ico
        ├── globals.css
        ├── layout.tsx
        ├── page.tsx
        ├── privacy-policy
        │   └── page.tsx
        ├── projects
        │   ├── [slug]
        │   │   └── page.tsx
        │   └── page.tsx
        ├── resume
        │   └── page.tsx
        ├── resume.tsx
        └── terms-of-service
            └── page.tsx
│   ├── styles/               # Global and component-specific styles
│   │   ├── globals.css       # Global CSS styles
│   │   ├── tailwind.css      # Tailwind styles
│   ├── lib/                  # Utility functions
│   │   ├── markdown.ts       # Markdown parser setup (MDX/Remark)
│   │   ├── metadata.ts       # Helper for frontmatter metadata
│   ├── content/              # Markdown content storage
│       ├── articles
        ├── legal
        │   ├── privacy_policy.md
        │   └── terms_of_service.md
        ├── projects
        ├── templates
        │   ├── articles.md
        │   ├── projects.md
        │   └── work.md
        └── work
            ├── barndoors-for-sale.md
            ├── bernier-llc.md
            ├── fractional-consulting.md
            ├── mparticle.md
            ├── resume.md
            ├── sendgrid.md
            ├── shapeshift.md
            ├── stealth-startup-2509.md
            ├── temporal.md
            └── twilio.md 
├── .gitignore                # Git ignore file
├── next.config.js            # Next.js configuration file
├── tailwind.config.js        # Tailwind CSS config
├── tsconfig.json             # TypeScript configuration
├── package.json              # Dependencies and scripts
└── README.md                 # Project documentation
