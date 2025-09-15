# Replit.md

## Overview

This is a personal portfolio website showcasing a full-stack developer's skills and projects. The portfolio includes an about section, project showcases, skills overview, and contact information. The site is built as a static website using HTML, CSS, and JavaScript with multiple page examples demonstrating different types of web applications including a weather app, contact catalog, and gym advertisement page.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Static Website Structure**: The project uses a traditional multi-page HTML structure with a main landing page (`index.html`) and additional showcase pages in the `pages/` directory
- **Styling Framework**: Tailwind CSS is used as the primary CSS framework, loaded via CDN for rapid development and consistent styling
- **Typography**: Google Fonts integration (Inter and Lora font families) for improved visual appeal
- **Responsive Design**: Mobile-first responsive design using Tailwind's responsive utilities

### Page Structure
- **Main Portfolio Page** (`index.html`): Landing page with navigation, about section, and portfolio overview
- **Project Showcase Pages**: 
  - Contact catalog application (`pages/contact.html`)
  - Weather application (`pages/weather_app.html`) 
  - Gym advertisement page (`pages/daily.html`)
  - Additional showcase page (`pages/ema.html`)

### JavaScript Architecture
- **Vanilla JavaScript**: Uses plain JavaScript without frameworks for lightweight functionality
- **Event-Driven Interactions**: Handles user interactions for form submissions, weather API calls, and dynamic content updates
- **Modular Approach**: Each page contains its own JavaScript logic embedded within the HTML files

### Styling Approach
- **Utility-First CSS**: Leverages Tailwind CSS for rapid styling without custom CSS files
- **Component-Based Styling**: Consistent styling patterns across different pages
- **Custom CSS Overrides**: Minimal custom styles for specific design requirements (animations, custom colors)

## External Dependencies

### CSS Frameworks and Libraries
- **Tailwind CSS**: Primary CSS framework loaded via CDN
- **Font Awesome**: Icon library for UI elements

### Fonts
- **Google Fonts**: 
  - Inter font family for body text
  - Lora font family for headings
  - Roboto font family for specific pages

### Development Tools
- **Semgrep**: Security analysis tool with configuration for code quality and security scanning

### APIs (Implied from Weather App)
- **Weather API**: The weather application suggests integration with external weather data services for real-time weather information

### Browser APIs
- **Geolocation API**: Likely used in the weather application for location-based weather data
- **Fetch API**: For making HTTP requests to external services

The architecture prioritizes simplicity, performance, and maintainability while showcasing various web development capabilities through different application examples.