# Kid to Kid Garner Website

This is the official website for Kid to Kid Garner, located at 2690 Timber Drive in Garner, NC. The site provides additional information and resources to complement the [official Kid to Kid store page](https://kidtokid.com/garner).

## 🌐 Live Site

- Production: [https://www.k2kgarner.com](https://www.k2kgarner.com)
- Official Store Page: [https://kidtokid.com/garner](https://kidtokid.com/garner)

## 🏗️ Tech Stack

- **Framework:** [Astro](https://astro.build)
- **Styling:** [Tailwind CSS v4](https://tailwindcss.com)
- **Deployment:** Cloudflare Pages via Wrangler
- **Adapter:** @astrojs/cloudflare

## 📂 Project Structure

```text
/
├── brand-kit.md           # Brand guidelines and design system
├── public/                # Static assets
├── src/
│   ├── components/        # Astro components
│   │   └── Navigation.astro
│   ├── layouts/           # Page layouts
│   │   └── Layout.astro
│   ├── pages/             # Page routes
│   │   ├── index.astro    # Home page
│   │   ├── how-to-sell.astro
│   │   ├── location.astro
│   │   ├── contact.astro
│   │   └── about.astro
│   └── styles/
│       └── global.css     # Global styles and Tailwind config
└── wrangler.toml          # Cloudflare Pages config
```

## 🚀 Commands

| Command | Action |
| :--- | :--- |
| `npm install` | Install dependencies |
| `npm run dev` | Start dev server at `localhost:4321` |
| `npm run build` | Build production site to `./dist/` |
| `npm run preview` | Preview build locally |
| `npm run deploy` | Build and deploy to Cloudflare Pages |
| `npm run cf-typegen` | Generate Cloudflare Worker types |

## 🎨 Brand Guidelines

See [brand-kit.md](./brand-kit.md) for complete brand guidelines including:
- Color palette
- Typography
- Voice and tone
- Component styles
- Usage guidelines

## 🚀 Deployment

This site is configured for deployment to Cloudflare Pages using Wrangler.

### First-time Setup

1. Install Wrangler globally (optional): `npm install -g wrangler`
2. Log in to Cloudflare: `npx wrangler login`
3. Deploy: `npm run deploy`

### Subsequent Deployments

```bash
npm run deploy
```

This will build the site and deploy it to Cloudflare Pages. The production URL will be https://www.k2kgarner.com.

### Cloudflare Pages Setup

The site uses the Cloudflare Pages adapter with the following configuration:
- Build command: `npm run build`
- Build output directory: `dist`
- Node version: 18 or higher

## 📝 Content Updates

The site content is derived from:
1. Official Kid to Kid franchise information
2. Local Garner store details
3. Store process documentation (from Google Docs)

To update FAQ content, modify `/src/pages/how-to-sell.astro`.

## 📍 Store Information

**Kid to Kid Garner**
2690 Timber Drive
Garner, NC 27529

**Phone:** 919-322-2445
**Email:** garner@kidtokid.com

**Store Hours:**
Mon-Sat: 10am - 7pm
Sun: 10am - 3pm

**Buying Hours:**
M/W/F: 10am - 2pm
T/Th/Sat: 10am - 6pm

## 🤝 Contributing

This is a local business website. For content updates or technical issues, please contact the store directly.

## 📄 License

© 2025 Kid to Kid Garner. Part of the Kid to Kid franchise.
