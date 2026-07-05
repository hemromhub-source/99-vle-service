# 99 VLE Service - Professional Document Crop & Print Tool

A comprehensive web application for ID card cropping, print layouts, and photo manipulation tools built with modern web technologies.

## 🎯 Project Overview

**99 VLE Service** provides professional-grade tools for:
- 🪪 ID Card Cropping (Aadhaar, PAN, Voter ID, Driving Licence, Ayushman, ABHA, e-Shram, Passport, Ration Card, NREGA Job Card)
- 🖨️ Print Layouts (A4 formats with multiple copy options)
- 📷 Photo Tools (Passport photo maker, signature crop, background removal, resize, compress)

## 🛠️ Technology Stack

- **Frontend**: Next.js 14+ with React
- **Styling**: Tailwind CSS
- **Image Manipulation**: Fabric.js, React Easy Crop
- **Database**: MongoDB
- **Deployment**: Vercel
- **UI/UX**: Professional, Mobile-responsive design

## 📦 Project Structure

```
99-vle-service/
├── app/                          # Next.js app directory
│   ├── layout.tsx                # Root layout
│   ├── page.tsx                  # Home page
│   ├── (auth)/                   # Authentication routes
│   ├── (tools)/                  # Tool routes
│   │   ├── id-cards/             # ID card cropping tools
│   │   ├── print-layouts/        # Print layout tools
│   │   └── photo-tools/          # Photo manipulation tools
│   └── admin/                    # Admin dashboard
├── components/                   # Reusable React components
│   ├── common/                   # Shared components (Navbar, Footer, etc.)
│   ├── tools/                    # Tool-specific components
│   └── layouts/                  # Layout components
├── lib/                          # Utility functions
│   ├── db/                       # Database configuration
│   ├── api/                      # API utilities
│   └── utils/                    # Helper functions
├── public/                       # Static assets
├── styles/                       # Global styles
├── config/                       # Configuration files
└── docs/                         # Documentation & roadmap
```

## ✨ Core Features (Per Tool)

- ✅ Upload Image (drag & drop support)
- ✅ Zoom
- ✅ Rotate
- ✅ Drag
- ✅ Auto Crop
- ✅ Download JPG
- ✅ Download PNG
- ✅ Print
- ✅ Mobile Friendly

## 🎨 Professional Standards

- 📂 Clean, scalable folder structure
- 🎨 Professional UI with consistent design system
- ⚡ Fast loading & optimized performance
- 📱 Mobile responsive (100% mobile-friendly)
- 🔍 SEO-friendly pages
- 🔒 Secure coding practices
- 🧩 Reusable, modular components

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/hemromhub-source/99-vle-service.git
cd 99-vle-service

# Install dependencies
npm install

# Run development server
npm run dev

# Open browser
# http://localhost:3000
```

## 📋 Development Roadmap

### Phase 1: Foundation (Lessons 1-10)
- [ ] Project Setup
- [ ] Professional Homepage
- [ ] Navbar & Footer
- [ ] Aadhaar Crop Tool
- [ ] PAN Crop Tool
- [ ] Voter ID Crop Tool
- [ ] Driving Licence Crop Tool
- [ ] Ayushman Card Crop Tool
- [ ] ABHA Card Crop Tool
- [ ] e-Shram Card Crop Tool

### Phase 2: Advanced Cropping (Lessons 11-20)
- [ ] Passport Crop Tool
- [ ] Ration Card Crop Tool
- [ ] NREGA Job Card Crop Tool
- [ ] Print Layout System
- [ ] Database Integration
- [ ] User Authentication
- [ ] Admin Panel Basics
- [ ] More features...

### Phase 3: Photo Tools & Optimization (Lessons 21-40)
- [ ] Passport Photo Maker
- [ ] Signature Crop
- [ ] Background White
- [ ] Resize Tool
- [ ] Compress Tool
- [ ] Performance Optimization
- [ ] SEO Enhancement

### Phase 4: Deployment & Polish (Lessons 41-50)
- [ ] Admin Dashboard Complete
- [ ] Security Hardening
- [ ] Testing & QA
- [ ] Documentation
- [ ] Deploy on BestToolLab.in
- [ ] Post-deployment monitoring

## 📖 Documentation

- [Database Design](./docs/database-design.md)
- [Component Architecture](./docs/component-architecture.md)
- [API Documentation](./docs/api-docs.md)
- [Crop Templates](./docs/crop-templates.md)
- [Print Engine](./docs/print-engine.md)

## 🔐 Security

- Secure file uploads
- Input validation
- Protected admin routes
- Secure API endpoints

## 📄 License

MIT

## 👥 Contributing

Contributions are welcome! Please follow the project's coding standards and create feature branches.

---

**Built with ❤️ for professional document management**
