# Problem-Solving Practice Case Studies

A simple, interactive website for practicing problem-solving skills through real-world scenarios. Users work through three different case studies and submit their responses via forms.

## 🎯 Overview

This site presents three problem-solving scenarios:
1. **Daily Operations** - Betty's Bakery inventory management (5 minutes)
2. **Group Problem-Solving** - Community garden utilization (5 minutes) 
3. **Communication Challenge** - Library book club attendance (5 minutes)

**Total completion time:** ~20 minutes

## 🚀 Live Demo

Visit the live site: [a-case-study.netlify.app](https://a-case-study.netlify.app/)

## ✨ Features

- **Responsive design** - Works on desktop and mobile
- **Interactive forms** - Collect user responses for each case study
- **Email notifications** - Get notified when users submit responses
- **CSV export** - Download all responses from Netlify dashboard
- **Clean UI** - Simple, accessible design focused on the content
- **Fast deployment** - One-click deploy to Netlify

## 🏗️ Project Structure

```
├── index.html          # Main page with all case studies
├── _redirects          # Netlify SPA routing configuration
├── success.html        # Custom thank you page (optional)
├── netlify.toml        # Netlify configuration (optional)
└── README.md          # This file
```

## 🔧 Setup & Installation

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/iamctodd/case-study-site.git
   cd case-study-site
   ```

2. **Open locally**
   ```bash
   # Simple HTTP server
   python -m http.server 8000
   # Or use any local server of your choice
   ```

3. **Visit** `http://localhost:8000`

### Deploy to Netlify

#### One-Click Deploy
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/iamctodd/case-study-site)

## 📝 Form Configuration

The site uses **Netlify Forms** to collect responses. Forms are automatically detected and configured during deployment.

### Form Names
- `bakery-response` - Case 1: Bakery scenario
- `garden-response` - Case 2: Community garden scenario  
- `library-response` - Case 3: Library book club scenario

### Response Fields
Each form collects:
- Participant name (optional)
- Session date
- Three problem-solving questions specific to each case

## 🛠️ Customization

### Adding New Case Studies

1. **Copy existing form structure** in `index.html`
2. **Change form name** attribute: `name="new-case-response"`
3. **Update hidden form-name field**: `value="new-case-response"`
4. **Customize questions** and form fields as needed

### Styling Changes

The site uses **Tailwind CSS classes** embedded in the HTML. Key classes:
- `bg-blue-600` - Button colors
- `text-blue-700` - Question text color
- `border-blue-300` - Input borders
- `space-y-4` - Vertical spacing

### Common Response Patterns
Track themes in user responses:
- Problem identification accuracy
- Solution creativity and practicality
- Customer empathy and understanding

## 🤝 Contributing

1. **Fork the repository**
2. **Create feature branch**: `git checkout -b feature/new-case-study`
3. **Commit changes**: `git commit -am 'Add new case study'`
4. **Push to branch**: `git push origin feature/new-case-study`
5. **Submit pull request**

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🎉 Acknowledgments

- Built for practicing real-world problem-solving skills
- Designed for accessibility and ease of use
- Powered by Netlify's excellent form handling
- Thanks to the open-source community for tools and inspiration

