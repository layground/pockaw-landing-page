# **Pockaw \- Your Finance Buddy**

## **📖 Overview**

This repository contains the **official landing page** for [Pockaw](https://github.com/layground/pockaw), a modern cross-platform application designed to help users track expenses, manage budgets, and achieve financial goals.

The landing page is engineered for high performance, SEO optimization, and a fully responsive user experience across mobile, tablet, and desktop devices. It adheres to modern web standards and utilizes utility-first CSS for rapid UI development.

## **✨ Key Features**

* **Responsive Design:** Fluid layouts that adapt seamlessly to any screen size using Tailwind CSS breakpoints.  
* **Modern UI/UX:** Sleek aesthetics aligned with the Pockaw mobile application's design language.  
* **SEO Optimized:** Includes sitemap.xml, robots.txt, and semantic HTML structure for better search engine visibility.  
* **Asset Optimization:** Utilizes optimized WebP images for faster load times.  
* **Legal Compliance:** dedicated pages for Privacy Policy and Terms & Conditions.

## **🛠 Tech Stack**

* **Core:** Semantic HTML5  
* **Styling:** [Tailwind CSS](https://tailwindcss.com/)  
* **Package Management:** npm  
* **Font Family:** Montserrat & Urbanist

## **📂 Project Structure**

pockaw-landing-page/  
├── src/  
│   ├── assets/  
│   │   └── images/       \# WebP and PNG assets  
│   ├── favicon\_io/       \# Favicon generation assets  
│   ├── index.html        \# Main entry point  
│   ├── privacy-policy.html  
│   ├── terms-and-conditions.html  
│   ├── input.css         \# Tailwind directives  
│   ├── output.css        \# Compiled CSS (Production build)  
│   ├── robots.txt  
│   └── sitemap.xml  
├── package.json          \# Dependencies and scripts  
├── tailwind.config.js    \# Tailwind configuration  
└── .gitignore

## **🚀 Getting Started**

Follow these instructions to set up the project locally for development.

### **Prerequisites**

* [Node.js](https://nodejs.org/) (LTS version recommended)  
* npm (comes with Node.js)

### **Installation**

1. **Clone the repository:**  
   git clone [https://github.com/layground/pockaw](https://github.com/layground/pockaw)  
   cd pockaw-landing-page

2. **Install dependencies:**  
   npm install

### **💻 Development**

To start the Tailwind CLI in watch mode (hot-reloading CSS changes):

```bash
npx tailwindcss \-i ./src/input.css \-o ./src/output.css \--watch
```

Open src/index.html in your browser (or use an extension like Live Server in VS Code) to see changes in real-time.

### **🏗 Production Build**

To minify the CSS for production deployment:

```bash
npx tailwindcss \-i ./src/input.css \-o ./src/output.css \--minify
```

## **🎨 Design System & Assets**

The project uses a custom tailwind.config.js to extend the default theme, ensuring brand consistency with the Pockaw mobile app.

* **Primary Colors:** Derived from the Pockaw brand palette.  
* **Typography:** Configured to use Montserrat and Urbanist.

## **🤝 Contributing**

1. Fork the Project  
2. Create your Feature Branch (`git checkout \-b feature/amazing-feature`)  
3. Commit your Changes (`git commit \-m 'Add some amazing-feature'`)  
4. Push to the Branch (`git push origin feature/amazing-feature`)  
5. Open a Pull Request

## **📄 License**

Distributed under the MIT License. See LICENSE for more information.

Built with ❤️ by the Pockaw Team
