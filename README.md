# StreakNFitness Website

Professional fitness solutions website built with modern web standards and SEO optimization.

## 🚀 Features

- **SEO Optimized**: Complete meta tags, structured data, and semantic HTML
- **Performance Focused**: Optimized loading, lazy loading, and efficient animations
- **Mobile Responsive**: Fully responsive design that works on all devices
- **Accessibility**: WCAG compliant with proper focus states and semantic markup
- **Security**: Content Security Policy, XSS protection, and form validation
- **Analytics**: Integrated with Cloudflare Web Analytics
- **Contact Form**: Secure contact form with reCAPTCHA v3 protection

## 📁 File Structure

```
├── index.html          # Main homepage
├── robots.txt          # Search engine crawling instructions
├── sitemap.xml         # XML sitemap for search engines
├── site.webmanifest    # PWA manifest file
├── .htaccess          # Apache server configuration
└── README.md          # This file
```

## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd streaknfit-website
   ```

2. **Configure reCAPTCHA**
   - Replace the reCAPTCHA site key in `index.html`
   - Update the Formspree endpoint if needed

3. **Update Content**
   - Modify testimonials, stats, and content as needed
   - Add your actual favicon files
   - Update social media links and contact information

4. **Deploy**
   - Upload files to your web server
   - Ensure HTTPS is enabled
   - Test contact form functionality

## 🔧 Customization

### Colors
The website uses a clean color palette:
- Primary: `#007aff` (Blue)
- Text: `#1d1d1f` (Dark Gray)
- Secondary Text: `#6e6e73` (Light Gray)
- Background: `#ffffff` (White)
- Section Background: `#f5f5f7` (Light Gray)

### Typography
- Font Family: Apple system fonts with fallbacks
- Headings: 700 weight
- Body: 400 weight
- UI Elements: 500-600 weight

### Sections
1. **Hero**: Main value proposition and CTA
2. **Features**: Core service offerings
3. **Stats**: Social proof with numbers
4. **Testimonials**: Client feedback
5. **Contact**: Contact form and information

## 📊 SEO Features

- Complete meta tags (title, description, keywords)
- Open Graph tags for social sharing
- Twitter Card tags
- Structured data (JSON-LD)
- Canonical URLs
- XML sitemap
- Robots.txt
- Semantic HTML structure

## 🔒 Security Features

- reCAPTCHA v3 integration
- Form input sanitization
- Rate limiting on form submissions
- Security headers via .htaccess
- XSS protection
- Content type validation

## 📱 Performance Optimizations

- Efficient CSS with minimal unused styles
- Throttled scroll events
- Intersection Observer for animations
- Preconnect to external domains
- Compressed assets via .htaccess
- Proper caching headers

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📞 Contact Form

The contact form uses:
- Formspree for form handling
- reCAPTCHA v3 for spam protection
- Client-side validation
- Success/error messaging
- Rate limiting

## 🚀 Deployment Checklist

- [ ] Update reCAPTCHA keys
- [ ] Test contact form
- [ ] Add favicon files
- [ ] Update social media links
- [ ] Test on mobile devices
- [ ] Verify HTTPS setup
- [ ] Submit sitemap to search engines
- [ ] Set up analytics tracking

## 📈 Analytics

The site includes Cloudflare Web Analytics. Update the token in the script tag at the bottom of `index.html`.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License.
