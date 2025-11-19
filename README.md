# Tech by Jenish - Portfolio & Blog

My personal portfolio and technical blog documenting my journey in distributed systems, cloud architecture, and software engineering.

## 🚀 Tech Stack

- **Framework**: Jekyll
- **Theme**: Minimal Mistakes
- **Hosting**: GitHub Pages
- **Plugins**: SEO, Feed, Paginate, Sitemap

## 🛠️ Local Development

### Prerequisites
- Ruby (2.7+)
- Bundler
- Git

### Setup

1. **Clone the repository**
```bash
git clone https://github.com/jenishk20/jenishk20.github.io.git
cd jenishk20.github.io
```

2. **Install dependencies**
```bash
bundle install
```

3. **Run locally**
```bash
bundle exec jekyll serve
```

4. **View in browser**
Open [http://localhost:4000](http://localhost:4000)

### Development with Live Reload
```bash
bundle exec jekyll serve --livereload
```

## 📝 Writing Posts

Create new posts in the `_posts` directory with the format:
```
YYYY-MM-DD-title-of-post.md
```

### Post Front Matter Template
```yaml
---
layout: single
title: "Your Post Title"
date: YYYY-MM-DD
categories: [category1, category2]
tags: [tag1, tag2, tag3]
excerpt: "Brief description of your post"
toc: true
toc_sticky: true
---
```

## 🎨 Theme Customization

The site uses the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) theme.

### Change Theme Skin
Edit `_config.yml`:
```yaml
minimal_mistakes_skin: "dark"  # Options: default, air, aqua, contrast, dark, dirt, neon, mint, plum, sunrise
```

### Custom Styling
Add custom CSS in `assets/css/main.scss`

## 📂 Project Structure

```
jenishk20.github.io/
├── _config.yml          # Site configuration
├── _posts/              # Blog posts
├── _data/               # Data files (navigation, etc.)
├── assets/              # Images, CSS, JS
│   └── images/          # Image assets
├── about.md             # About page
├── index.md             # Home page
└── Gemfile              # Ruby dependencies
```

## 🌐 Deployment

The site automatically deploys to GitHub Pages when you push to the `main` branch.

### Manual Deploy
```bash
git add .
git commit -m "Your commit message"
git push origin main
```

## 📊 Features

- ✅ Responsive design
- ✅ Dark mode support
- ✅ Table of contents for posts
- ✅ Author profile sidebar
- ✅ Social media links
- ✅ SEO optimized
- ✅ RSS feed
- ✅ Code syntax highlighting
- ✅ Category and tag archives
- ✅ Related posts

## 🔗 Links

- **Live Site**: [https://jenishk20.github.io](https://jenishk20.github.io)
- **GitHub**: [@jenishk20](https://github.com/jenishk20)
- **LinkedIn**: [Jenish Kothari](https://linkedin.com/in/jenishkothari)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this repository and use it as a template for your own portfolio!

---

Built with ❤️ using Jekyll and Minimal Mistakes