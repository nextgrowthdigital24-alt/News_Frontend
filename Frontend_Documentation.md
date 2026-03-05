# Frontend - News Website 📰

This is the React-based frontend for the News Website project, built with Vite and modern React patterns.

## 🚀 Tech Stack

- **Framework:** [React 18](https://reactjs.org/)
- **Build Tool:** [Vite](https://vitejs.dev/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **UI Components:** [shadcn/ui](https://ui.shadcn.com/) (based on Radix UI)
- **Data Fetching:** [TanStack Query (React Query)](https://tanstack.com/query/latest)
- **Routing:** [React Router 6](https://reactrouter.com/)
- **Icons:** [Lucide React](https://lucide.dev/)
- **SEO/Meta Tags:** [React Helmet Async](https://github.com/staylor/react-helmet-async)

## 📁 Project Structure

- `src/components`: Reusable UI components and domain-specific features
- `src/pages`: Top-level page components and routing entry points
- `src/context`: React context providers for global state
- `src/hooks`: Custom React hooks for shared logic
- `src/lib`: Shared utility functions and API client definitions
- `src/data`: Static data and configuration constants

## 🛠️ Key Features

- **Responsive News Feed:** Dynamic headlines and category-based filtering
- **Article Detail Page:** Full article view with dynamic SEO meta-tag injection support
- **Category & Subcategory Views:** Hierarchical navigation for in-depth browsing
- **Search:** Real-time search functionality across the article database
- **Mobile Menu:** Intuitive hamburger navigation for smaller viewports
- **SEO Ready:** Optimized for social media sharing and search engine indexing via server-side meta injection

## ⚙️ Getting Started

### Prerequisites

- Node.js (v18 or higher recommended)
- npm or yarn

### Installation

```bash
cd frontend
npm install
```

### Development

Run the Vite development server:

```bash
npm run dev
```

### Production Build

Build the optimized production assets:

```bash
npm run build
```

Preview the production build locally:

```bash
npm run preview
```

## 🌐 Environment Variables

Create a `.env` file in the `frontend` root:

```env
VITE_API_URL=https://your-api-server.com/api
```

## 📦 Deployment Note

This project includes a built-in SEO server (`server.js`) for production deployments that require dynamic Open Graph tags for social media previews. When deploying as a standalone, you can start this server:

```bash
npm start
```
