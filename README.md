# 🌿 Plant Shop

A sleek and intuitive e-commerce application designed for green thumbs. **Plant Shop** allows users to browse a diverse collection of indoor and outdoor plants, view detailed information, and manage their selections using a dynamic shopping cart.



## ✨ Features

* **Curated Catalog**: Browse a wide variety of plants with high-quality images and descriptions.
* **Dynamic Shopping Cart**: Add, remove, and update plant quantities in real-time.
* **Persistent State**: Your cart remains saved across sessions using advanced state management.
* **Smooth UX**: Integrated with **Lenis** for smooth scrolling and **React Hot Toast** for instant feedback.
* **Responsive Design**: Fully optimized for mobile, tablet, and desktop using **Tailwind CSS**.

## 🛠️ Tech Stack

* **Frontend**: [React 19](https://react.dev/)
* **Build Tool**: [Vite](https://vitejs.dev/)
* **State Management**: [Zustand](https://github.com/pmndrs/zustand) & [Redux Toolkit](https://redux-toolkit.js.org/)
* **Database/Auth**: [Supabase](https://supabase.com/)
* **Styling**: [Tailwind CSS](https://tailwindcss.com/), [Styled Components](https://styled-components.com/), & [Sass](https://sass-lang.com/)
* **Icons**: [React Icons](https://react-icons.github.io/react-icons/)

## 🚀 Getting Started

### Prerequisites
* Node.js (v18 or higher)
* npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone [https://github.com/your-username/plant-shop.git](https://github.com/your-username/plant-shop.git)
   cd plant-shop
   ```

2. **Install dependencies**

  ```bash
    npm install
  ```


3. **Set up Environment Variables Create a .env file in the root directory and add your Supabase credentials:**
  
  ```bash
  VITE_SUPABASE_URL=your_supabase_url
  VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
  ```

4. Run the development server
  ```bash
    npm run dev
  ```

Open http://localhost:5173 to view it in your browser.

5. **📦 Deployment**
  To create a production build:
  ```bash
    npm run build
  ```
The static files will be generated in the dist folder, ready for hosting on GitHub Pages, Vercel, or Netlify.
