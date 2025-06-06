# Professional Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- Responsive design that works on all devices
- Smooth scrolling navigation
- Animated skill bars
- Contact form
- Social media links
- Project showcase
- Education and certification sections
- Skills visualization
- Mobile-friendly navigation

## Setup Instructions

1. Clone or download this repository
2. Add your profile picture as `profile.jpg` in the root directory
3. Update the content in `index.html` with your personal information:
   - Update social media links
   - Add your education details
   - Add your certifications
   - Add your projects
   - Update skills
   - Customize the about section
4. Customize the colors in `styles.css` by modifying the CSS variables in the `:root` selector
5. Open `index.html` in your browser to view the website

## Customization

### Colors
You can customize the color scheme by modifying these variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --text-color: #1f2937;
    --light-text: #6b7280;
    --background: #ffffff;
    --section-bg: #f3f4f6;
}
```

### Profile Picture
Replace the `profile.jpg` file with your own photo. The recommended size is 400x400 pixels.

### Social Media Links
Update the social media links in the HTML file with your profiles:
```html
<a href="https://linkedin.com/in/your-profile" target="_blank">
<a href="https://github.com/your-username" target="_blank">
<a href="https://hackerrank.com/your-profile" target="_blank">
```

### Contact Form
The contact form is currently set up to show a success message. To make it functional, you'll need to:
1. Set up a backend server to handle form submissions
2. Update the form submission handler in `script.js` to send data to your server

## Browser Support

The website is compatible with:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License. 