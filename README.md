
# 🎶 Music Academy Website

A modern, responsive web application built with **Next.js 13+ (App Router)**, **TypeScript**, and **Tailwind CSS**.  
The project showcases courses, instructors, testimonials, and more for a music learning platform.

---

## 🚀 Tech Stack
- [Next.js 13+](https://nextjs.org/) (App Router)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [UI](https://ui.aceternity.com/) for prebuilt UI components
- [Lucide Icons](https://lucide.dev/) for modern icons

---

## 📂 Project Structure
```

src/
├── app/                   # Next.js App Router pages
│   ├── contact/           # Contact page
│   ├── courses/           # Courses page
│   ├── favicon.ico        # Site favicon
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Home page
│
├── components/            # Reusable components
│   ├── ui/                # UI animations & effects
│   │   ├── wavy-background.tsx
│   │   └── animated-tooltip.tsx
│   ├── FeaturedCourses.tsx
│   ├── Footer.tsx
│   ├── HeroSection.tsx
│   ├── Instructors.tsx
│   ├── Navbar.tsx
│   ├── TestimonialCards.tsx
│   ├── UpcomingWebinars.tsx
│   └── WhyChooseUs.tsx
│
├── data/                  # Static JSON data
│   └── music\_courses.json
│
├── utils/                 # Utility functions
│   └── cn.ts
│
├── next-env.d.ts          # Next.js types
├── next.config.mjs        # Next.js configuration
└── package.json           # Dependencies

````

---

## 🛠️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/music-academy.git
   cd music-academy
````

2. Install dependencies:

   ```bash
   npm install
   # or
   yarn install
   ```

3. Run the development server:

   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 🌟 Features

* 🎵 **Hero Section** with modern gradient background
* 🎤 **Meet Our Instructors** section with animated tooltips
* 📚 **Featured Courses** powered by JSON data
* ⭐ **Testimonials** with styled cards
* 🎹 **Why Choose Us** section highlighting platform benefits
* 📅 **Upcoming Webinars** showcase
* 📩 **Contact Page** with form

---

## 🔧 Configuration

* Update `next.config.mjs` for remote image patterns if you’re fetching external images.
* Add course/instructor data in `src/data/music_courses.json`.

---

## 📦 Deployment

You can deploy the project easily on:

* [Vercel](https://vercel.com/) (recommended for Next.js)
* [Netlify](https://www.netlify.com/)

Build command:

```bash
npm run build


## 👨‍💻 Author

Developed by **Prem Kumar**
