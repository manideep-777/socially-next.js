# Socially - Next.js Social Media Platform

A modern, full-stack social media application built with Next.js 14, featuring real-time interactions, file uploads, and a sleek user interface.

## 🌐 Live Demo

<a href="https://socially-next-js-chi.vercel.app/" target="_blank" rel="noopener noreferrer">Visit Socially</a>

## ✨ Highlights

🚀 **Tech stack**: Next.js App Router, Postgres, Prisma, Clerk & TypeScript  
💻 **Server Components**, Layouts, Route Handlers, Server Actions  
🔥 **Special Files**: loading.tsx, error.tsx, not-found.tsx  
📡 **API Integration** using Route Handlers  
🔄 **Data Fetching**, Caching & Revalidation  
🎭 **Client & Server Components**  
🛣️ **Dynamic & Static Routes**  
🎨 **Styling** with Tailwind & Shadcn  
🔒 **Authentication & Authorization**  
📤 **File Uploads** with UploadThing  
🗃️ **Database Integration** with Prisma  
🚀 **Server Actions & Forms**  
⚡ **Optimistic Updates**  

## 🛠️ Tech Stack

<div align="center">

<a href="https://reactjs.org" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React"/>
</a>
<a href="https://nextjs.org" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white" alt="Next.js"/>
</a>
<a href="https://www.typescriptlang.org/" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
</a>
<a href="https://tailwindcss.com/" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS"/>
</a>
<a href="https://clerk.com/" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Clerk-6C47FF?style=for-the-badge&logo=clerk&logoColor=white" alt="Clerk"/>
</a><br>
<a href="https://www.postgresql.org/" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL"/>
</a>
<a href="https://www.prisma.io/" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Prisma-3982CE?style=for-the-badge&logo=Prisma&logoColor=white" alt="Prisma"/>
</a>
<a href="https://vercel.com/" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel"/>
</a>

</div>


### Core Technologies

- **⚛️ React 18** - Frontend library with latest features
- **🔷 Next.js 14** - Full-stack React framework with App Router
- **📘 TypeScript** - Type-safe development
- **🎨 Tailwind CSS** - Utility-first CSS framework
- **🔐 Clerk** - Authentication and user management
- **🐘 PostgreSQL** - Robust relational database
- **🔺 Prisma** - Next-generation ORM
- **📁 UploadThing** - File upload solution
- **🚀 Vercel** - Deployment and hosting platform

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm/yarn/pnpm
- PostgreSQL database

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd socially-nextjs
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   
   Create a `.env` file in the root directory:
   ```env
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   DATABASE_URL=your_postgresql_database_url
   UPLOADTHING_TOKEN=your_uploadthing_token
   ```

4. **Set up the database**
   ```bash
   npx prisma generate
   npx prisma db push
   ```

5. **Run the development server**
   ```bash
   npm run dev
   ```

6. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000)

## 📁 Project Structure

```
socially-nextjs/
├── app/                    # Next.js 14 App Router
│   ├── api/               # API Routes
│   ├── (auth)/            # Authentication pages
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   ├── loading.tsx        # Loading UI
│   ├── error.tsx          # Error UI
│   └── not-found.tsx      # 404 page
├── components/            # Reusable components
│   ├── ui/               # Shadcn UI components
│   └── ...               # Custom components
├── lib/                  # Utility functions
├── prisma/               # Database schema
├── public/               # Static assets
```

## 🎯 Features

- **🔐 Authentication**: Secure user authentication with Clerk
- **👤 User Profiles**: Customizable user profiles with avatars
- **📱 Responsive Design**: Mobile-first, fully responsive interface
- **📸 Media Uploads**: Image and file sharing capabilities
- **⚡ Real-time Updates**: Optimistic updates for seamless UX
- **🎨 Modern UI**: Clean, modern interface with Tailwind CSS
- **🛡️ Type Safety**: Full TypeScript integration
- **🚀 Performance**: Server-side rendering and caching

## 🧪 Development

### Available Scripts

```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run start        # Start production server
npm run lint         # Run ESLint
npm run type-check   # Run TypeScript checks
```

### Database Commands

```bash
npx prisma studio    # Open Prisma Studio
npx prisma generate  # Generate Prisma client
npx prisma db push   # Push schema changes
npx prisma db pull   # Pull schema from database
```

## 🌐 Deployment

This application is deployed on Vercel. To deploy your own instance:

1. Fork this repository
2. Connect your fork to Vercel
3. Add environment variables in Vercel dashboard
4. Deploy!

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/) - The React framework
- [Clerk](https://clerk.com/) - Authentication platform
- [Prisma](https://prisma.io/) - Database toolkit
- [Tailwind CSS](https://tailwindcss.com/) - CSS framework
- [Shadcn/ui](https://ui.shadcn.com/) - UI components
- [UploadThing](https://uploadthing.com/) - File uploads

---

<div align="center">
  <strong>Built with ❤️ using Next.js 14</strong>
</div>
