# 🌟 Muoki Anna - Portfolio Website

A modern, responsive portfolio website built with Next.js, TypeScript, and Tailwind CSS. This portfolio showcases my skills, projects, and provides an easy way to get in touch.

## 🚀 Features

- **Responsive Design** - Fully responsive across all devices (mobile, tablet, desktop)
- **Dark Theme** - Sleek dark mode interface for better user experience
- **Fast Performance** - Built with Next.js 14 for optimal loading speeds
- **Type Safety** - Full TypeScript implementation for robust code
- **Modern UI** - Clean and professional design with smooth animations
- **Contact Form** - Easy-to-use contact form for inquiries
- **Project Showcase** - Display of featured projects with details
- **Skills Section** - Visual representation of technical skills with logos

## 🛠️ Tech Stack

- **Framework:** Next.js 14
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Deployment:** Vercel (recommended)
- **Icons:** Devicons CDN for skill logos

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/muoki-anna/portfolio.git
cd portfolio
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## 📁 Project Structure

```
portfolio/
├── app/
│   ├── page.tsx          # Home page
│   ├── about/
│   │   └── page.tsx      # About page
│   ├── projects/
│   │   └── page.tsx      # Projects page
│   ├── contact/
│   │   └── page.tsx      # Contact page
│   └── layout.tsx        # Root layout
├── public/
│   └── images/           # Image assets
├── components/           # Reusable components
├── styles/              # Global styles
└── README.md
```

## 🎨 Pages

- **Home** - Hero section with introduction and featured projects
- **About** - Personal information, education, and experience
- **Projects** - Detailed showcase of portfolio projects
- **Contact** - Contact form and social media links

## 🔧 Customization

### Update Personal Information

Edit the following files to customize with your information:

- `app/page.tsx` - Update hero section text
- `app/about/page.tsx` - Update education and experience
- `app/contact/page.tsx` - Update contact details and social links
- `public/images/` - Add your profile picture

### Modify Skills

In `app/page.tsx`, update the skills array with your technologies:

```typescript
{ name: 'Your Skill', logo: 'logo-url' }
```

### Add Projects

Update the projects section in `app/projects/page.tsx` with your actual projects.

## 🚀 Deployment

### Deploy to Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com).

1. Push your code to GitHub
2. Import your repository on Vercel
3. Vercel will automatically detect Next.js and configure the build
4. Your site will be live in minutes!

### Deploy to Other Platforms

You can also deploy to:
- Netlify
- AWS Amplify
- Digital Ocean
- Railway

## 📝 Environment Variables

If you add any API integrations, create a `.env.local` file:

```bash
NEXT_PUBLIC_API_KEY=your_api_key_here
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

## 📧 Contact

- **Email:** muokianna10@gmail.com
- **Phone:** +254707819850
- **GitHub:** [@muoki-anna](https://github.com/muoki-anna)
- **LinkedIn:** [muoki-anna](https://linkedin.com/in/muoki-anna)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Next.js team for the amazing framework
- Tailwind CSS for the utility-first CSS framework
- Devicons for the skill logos

---

Made with ❤️ by Muoki Anna
