# Personal Website with Literary Works Portfolio

A modern, responsive personal website template featuring a dedicated section for showcasing literary works. This template is designed to be easily customizable and can be hosted on GitHub Pages.

## Features

- Clean and modern design
- Fully responsive layout
- Mobile-friendly navigation
- Dedicated literary works portfolio page
- Filter system for different types of works
- Smooth scrolling
- Social media integration
- Contact section

## Setup Instructions

1. Fork this repository to your GitHub account
2. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   ```
3. Customize the content:
   - Update the text in `index.html` with your personal information
   - Modify the literary works in `literary-works.html`
   - Add your own images to the `images` folder
   - Update social media links in both HTML files

## Customization Guide

### Updating Personal Information

1. Open `index.html` and modify:
   - Your name in the navigation and footer
   - The hero section content
   - About section text
   - Contact information and social media links

### Adding Literary Works

1. Open `literary-works.html`
2. Locate the `works-grid` section
3. Add new work items following the template:
   ```html
   <div class="work-item [category]">
       <div class="work-image">
           <img src="path-to-your-image" alt="Work Title">
       </div>
       <div class="work-info">
           <h3>Work Title</h3>
           <p class="genre">Genre: Your Genre</p>
           <p class="year">Published: Year</p>
           <p class="description">Your description here</p>
           <a href="#" class="read-more">Read More</a>
       </div>
   </div>
   ```

### Customizing Colors

1. Open `css/style.css`
2. Modify the color variables in the `:root` section:
   ```css
   :root {
       --primary-color: #your-color;
       --secondary-color: #your-color;
       --accent-color: #your-color;
       --text-color: #your-color;
       --light-bg: #your-color;
       --white: #ffffff;
   }
   ```

## Hosting on GitHub Pages

1. Go to your repository settings on GitHub
2. Scroll down to the "GitHub Pages" section
3. Select the branch you want to deploy (usually `main` or `master`)
4. Select the root folder as the source
5. Save the settings
6. Your website will be available at `https://your-username.github.io/repository-name`

## File Structure

```
├── index.html
├── literary-works.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/
│   └── hero-bg.jpg
└── README.md
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the LICENSE file for details. 