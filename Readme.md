# Jeevanrekha AI Health - Personalized Health Assistance Platform

DEPLOY LINK : https://life-line-ll9z9y8ac-pprincessjain-6036s-projects.vercel.app/

VIDEO DEMO LINK:

PPT LINK:

SNAPSHOTS:
<img width="1904" height="1030" alt="image" src="https://github.com/user-attachments/assets/d9241872-aab0-498c-bab9-98d94c1eeb04" />
















![Jeevanrekha](https://img.shields.io/badge/Jeevanrekha-AI%20Health-blue?style=for-the-badge)
![React](https://img.shields.io/badge/React-18+-61DAFB?logo=react&style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-5+-3178C6?logo=typescript&style=flat-square)
![Vite](https://img.shields.io/badge/Vite-5+-646CFF?logo=vite&style=flat-square)
![Supabase](https://img.shields.io/badge/Supabase-Backend-3ECF8E?logo=supabase&style=flat-square)

> **Jeevanrekha** means "Life Line" in Hindi - providing compassionate, intelligent health guidance powered by AI.

## 🎯 Overview

Jeevanrekha AI Health is a comprehensive health assistance platform that connects users with specialized AI coaches and disease information. The platform features:

- **10+ Specialized AI Coaches** - Each with unique expertise and color theme
- **Apollo Hospitals-style Disease Search** - Alphabetical browsing of 50+ diseases
- **Real-time AI Chat** - Fast, responsive health guidance
- **Dashboard Navigation** - Intuitive section-based navigation
- **Responsive Design** - Works seamlessly on desktop and mobile
- **Dark/Light Theme Support** - Personalized visual preferences
- **Supabase Integration** - Secure authentication and data management

---

## ⚡ Quick Start

### Prerequisites
- Node.js 18+ or Bun
- npm, yarn, or bun package manager

### Installation

```bash
# Clone the repository
git clone https://github.com/princessjainn/life-line.git
cd life-line

# Install dependencies
npm install
# or
yarn install
# or
bun install

# Create .env file with Supabase credentials
# VITE_SUPABASE_URL=your_supabase_url
# VITE_SUPABASE_PUBLISHABLE_KEY=your_supabase_publishable_key

# Start development server
npm run dev
```

The app will be available at `http://localhost:8082`

---

## 🎨 Key Features

### 🤖 Specialized AI Coaches (10+)

Each coach has unique expertise and distinct color branding:

| Coach | Color | Specialty |
|-------|-------|-----------|
| **General Wellness Coach** | Teal | Preventive • Personalized • Advisory |
| **Cardio Wellness Coach** | Red | Heart health & cardiovascular care |
| **Metabolic Health Coach** | Green | Metabolism & weight management |
| **Mental Wellness Coach** | Purple | Mental health & emotional support |
| **Musculoskeletal Coach** | Orange | Bones, joints & mobility |
| **Nutrition & Lifestyle Coach** | Lime | Diet & healthy living |
| **Women's Health** | Pink | Women-specific health concerns |
| **Senior Health** | Amber | Age-appropriate care strategies |
| **Child Health** | Sky Blue | Pediatric guidance |
| **Sleep Coach** | Indigo | Sleep quality & rest management |

### 🔍 Disease Search

- **Alphabetical Filtering** - A-Z letter buttons like Apollo Hospitals
- **50+ Diseases** - Comprehensive medical conditions database
- **Smart Search** - Filter by name, category, or description
- **Color-Coded Categories** - Visual organization by disease type
- **Instant AI Consultation** - Click to open chat about any disease

### 💬 AI Chat Features

- **Real-time Streaming** - Fast responses with streaming text
- **Coach-Specific Colors** - Dynamic UI adapts to selected coach
- **Message History** - View conversation flow
- **Type-Aware Theming** - Different themes for general vs disease-search
- **Optimized Performance** - Prevents duplicate API calls

### 📊 Dashboard Sections

1. **Dashboard Home** - Complete overview with all features
2. **All Coaches** - Full coach catalog
3. **Health Conditions** - Condition-specific information
4. **Disease Search** - Alphabetical disease browser
5. **Features** - Platform capabilities showcase

---

## 🛠️ Technology Stack

### Frontend
- **React 18** - UI framework
- **TypeScript** - Type safety
- **Vite** - Lightning-fast build tool
- **Tailwind CSS** - Utility-first styling
- **Framer Motion** - Smooth animations
- **shadcn/ui** - High-quality components
- **Lucide Icons** - Beautiful icon set

### Backend & Services
- **Supabase** - Authentication & Database
- **Edge Functions** - Serverless AI integration
- **PostgreSQL** - Data storage

### Development
- **ESLint** - Code quality
- **Vitest** - Testing framework
- **PostCSS** - CSS processing

---

## 📁 Project Structure

```
life-line/
├── src/
│   ├── components/
│   │   ├── AIChat.tsx                 # Chat interface
│   │   ├── DiseaseSearch.tsx          # Disease browser
│   │   ├── Navbar.tsx                 # Navigation
│   │   ├── ThemeToggle.tsx            # Dark/light mode
│   │   └── dashboard/
│   │       ├── DashboardCoaches.tsx   # Coaches grid
│   │       ├── DashboardConditions.tsx# Conditions grid
│   │       └── DashboardStats.tsx     # Stats display
│   │
│   ├── pages/
│   │   ├── Dashboard.tsx              # Main dashboard
│   │   ├── Index.tsx                  # Landing page
│   │   ├── Login.tsx                  # Authentication
│   │   └── Register.tsx               # User signup
│   │
│   ├── hooks/
│   │   ├── useAuth.tsx                # Auth management
│   │   └── use-toast.ts               # Toast notifications
│   │
│   └── integrations/
│       └── supabase/                  # Supabase setup
│
├── supabase/
│   ├── functions/                     # Edge functions
│   └── migrations/                    # Database schemas
│
└── [config files]
```

---

## 🚀 Usage Guide

### Getting Started
1. **Create Account** - Sign up with email
2. **View Dashboard** - Explore coaches and conditions
3. **Select a Coach** - Start chatting with specialized AI
4. **Ask Questions** - Get personalized health guidance
5. **Browse Diseases** - Use alphabetical search for conditions

### Navigate Dashboard
- **Sidebar** - Quick access to all sections
- **Coach Cards** - Select any coach to chat
- **Disease Search** - Browse 50+ conditions alphabetically
- **Health Conditions** - Condition-specific information

### Get Best Results
- Be specific with symptoms
- Mention symptom duration
- Include medical history
- Ask follow-up questions
- Remember: Always consult real doctors for serious issues

---

## 🎯 Performance Optimizations

✅ **Fast Response Times**
- Streaming responses
- Optimized API calls
- Efficient state management

✅ **Smooth Animations**
- Framer Motion transitions
- Page change animations
- Loading indicators

✅ **Responsive Design**
- Mobile-first approach
- Touch-friendly interface
- Collapsible sidebar

✅ **Accessibility**
- Semantic HTML
- ARIA labels
- Keyboard navigation

---

## 🔐 Security & Privacy

- **Secure Authentication** - Supabase auth
- **Encrypted Data** - Database encryption
- **Privacy Protection** - User data never shared
- **HIPAA Compliance** - Working towards full compliance

---

## 🤝 Contributing

Contributions welcome!

```bash
# 1. Fork the repository
# 2. Create feature branch
git checkout -b feature/amazing-feature

# 3. Commit changes
git commit -m 'Add amazing feature'

# 4. Push to branch
git push origin feature/amazing-feature

# 5. Open Pull Request
```

---

## 📋 Roadmap

**Q1 2026**
- [ ] Multi-language support
- [ ] Advanced analytics dashboard
- [ ] Health tracker integration

**Q2 2026**
- [ ] Video consultation feature
- [ ] Appointment scheduling
- [ ] Medical records storage

**Q3 2026**
- [ ] Insurance integration
- [ ] Prescription management
- [ ] Lab result analysis

---

## ⚠️ Medical Disclaimer

This platform provides health information but is **NOT** a substitute for professional medical advice. Always consult qualified healthcare professionals for serious health concerns.

---

## 📄 License

MIT License - see [LICENSE](LICENSE) file for details.

---

## 💬 Support

- 📧 Email: support@jeevanrekha.com
- 🐛 [Issues](https://github.com/princessjainn/life-line/issues)
- 💡 [Discussions](https://github.com/princessjainn/life-line/discussions)

---

## 🙏 Acknowledgments

- Built with ❤️ using React & TypeScript
- Powered by Supabase and AI
- UI from shadcn/ui
- Icons from Lucide
- Animations by Framer Motion

---

**Made with ❤️ for better health outcomes**

*Jeevanrekha - Your Personal Health Companion*
- Edit files directly within the Codespace and commit and push your changes once you're done.

## What technologies are used for this project?

This project is built with:

- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS
