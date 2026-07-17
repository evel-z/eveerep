# RVStore Portfolio

![RVStore Portfolio](https://images.unsplash.com/photo-1554118811-1e0d58224f24?auto=format&fit=crop&w=1200&q=80)

A modern, responsive, and aesthetically pleasing portfolio and landing page template built specifically for the **RVStore Digital Agency**. Designed to showcase premium digital assets, cafe/resto promotion services, and creative UI/UX projects.

## 🚀 Features

- **Premium Dark/Coffee Aesthetics**: A cohesive color palette inspired by coffee tones (Espresso, Beige, Peach) perfect for modern digital agencies.
- **Fluid & Responsive Typography**: Engineered with dynamic viewport units (`vw`) ensuring perfect scaling across all devices, from ultra-wide monitors to mobile screens.
- **Dynamic Hero Section**: Features staggered typography, overlapping character illustrations, and absolute positioning techniques for a "WOW" first impression.
- **Built with Laravel & Vanilla CSS**: Lightweight, fast, and dependency-free frontend design utilizing modern CSS Grid, Flexbox, and Media Queries.
- **Interactive UI**: Hover effects, drop shadows, and scale transforms to bring the digital showcase to life.

## 🛠️ Technology Stack

- **Backend Framework**: [Laravel 11](https://laravel.com/)
- **Frontend**: Blade Templating Engine, Vanilla HTML5, CSS3
- **Typography**: Google Fonts (Lilita One, Outfit, Playfair Display)

## 📦 Installation

To run this project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/rvstoredigi-ops/portofolio-rvstore.git
   cd portofolio-rvstore
   ```

2. **Install dependencies**
   ```bash
   composer install
   npm install
   ```

3. **Environment Setup**
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Run the development server**
   ```bash
   php artisan serve
   ```
   Visit `http://localhost:8000` in your browser.

## 📱 Mobile Responsiveness
This template has been meticulously optimized for mobile devices. Using `transform-origin` and fluid font sizes, the complex overlapping hero graphics maintain their exact desktop proportions on mobile screens without breaking overflow bounds.

---
*Designed & Developed by [RVStore](https://github.com/rvstoredigi-ops)*
