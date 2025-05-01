# All My Links - Personal Link-in-Bio Website

A clean, responsive link-in-bio website built with [HTML](https://www.freecodecamp.org/news/html-crash-course/), [CSS](https://www.freecodecamp.org/news/html-crash-course/)and [JavaScript](https://www.freecodecamp.org/news/html-crash-course/). Linktree was the inspiration, I just added some of my own vibes to it.

This website is hosted on [GitHub Pages](https://pages.github.com/), which gives you a free and easy way to share your website online from your GitHub account.


## What is a Link-in-Bio Website?

A link-in-bio website is a simple landing page that serves as a hub for all your online content. This project is a custom-built link page that you can host on GitHub Pages.

The design features a sleek dark theme with glassmorphic elements, smooth animations, and a fully responsive layout that adapts to any screen size. It's perfect for creators, professionals, and anyone who wants to share multiple links from their social media profiles.

## Features

- **Modern, Dark Theme Design** - Cool glass-like UI with smooth animations
- **Works on All Devices** - Looks good on phones, tablets and computers
- **Easy to Change** - Simple setup makes it easy to add your own stuff
- **Animated Elements** - Smooth fade-in animations and hover effects
- **FontAwesome Icons** - Nice icons for social media and content cards
- **Color Gradients** - Stylish color fades for visual appeal
- **Tag System** - Show off your skills and interests

## Before You Start

If you want to make something like this website, you should know a little bit about or be willing to learn:

- Basic [HTML](https://www.freecodecamp.org/learn/2022/responsive-web-design/) - How to structure web pages
- Basic [CSS](https://www.freecodecamp.org/learn/2022/responsive-web-design/) - How to style web pages
- Basic [Git](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control) - How to save your code changes
- [GitHub](https://github.com/about) - Where to store your code online
- [GitHub Pages](https://pages.github.com/) - How to put your website online for free

Don't worry if you're new to these! Here are some free resources to help you start:
- [FreeCodeCamp's Responsive Web Design](https://www.freecodecamp.org/learn/2022/responsive-web-design/) - Learn HTML & CSS basics
- [GitHub Pages Guide](https://pages.github.com/) - Official GitHub Pages documentation
- [Git Official Documentation](https://git-scm.com/doc) - Learn Git from the source
- [Visual Studio Code](https://code.visualstudio.com/docs/introvideos/basics) - Official VS Code tutorials

## Project Files

```
index.html          # Main webpage content
css/
  style.css         # All styling and animations
js/
  script.js         # JavaScript for future features
```

### What Each File Does

#### `index.html`
The main webpage file with:
- Header with your name and skill tags
- "Latest Stuff" section with featured content cards
- Social media links section
- Simple footer

#### `css/style.css`
Contains all the styling including:
- Dark theme with glass-like elements
- Mobile-friendly design
- Animation effects
- Card layouts and hover effects

#### `js/script.js`
A simple JavaScript file ready for any future features you might want to add.

##  How to Use This Project

This is my personal website that you can use as inspiration. Here's how:

### Option 1: Use this project as a starting point

1. **Get the Code**: Copy [this repository](https://github.com/lukepadiachy/all-my-stuff) to your GitHub account or download it to your computer
   ```
   git clone https://github.com/lukepadiachy/all-my-stuff.git
   ```

2. **Make It Yours**:
   - Change your name and intro text in the `<header>` section
   - Change the tags to show your own skills
   - Replace the content cards with your own projects
   - Update social media links to your profiles

3. **Change the Look** (If you want):
   - Change the colors by editing the CSS variables at the top of style.css
   - Change animations or layout if you know CSS

4. **Put It Online with GitHub Pages**:
   - Go to your repository settings on GitHub
   - Click on "Pages" in the left sidebar
   - Select your main branch (usually `main` or `master`)
   - Your website will be online at `https://yourusername.github.io/repository-name/`

### Option 2: Build your own from scratch

If you prefer to create your own link-in-bio site from scratch (which is a great way to learn!):

1. **Create a new repository on GitHub**:
   - Go to [GitHub](https://github.com) and log in
   - Click the "+" icon in the top right and select "New repository"
   - Name it something like "my-links" or "bio-links"
   - Initialize with a README

2. **Clone the repository to your computer**:
   ```
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

3. **Create the basic files**:
   ```
   touch index.html
   mkdir css js
   touch css/style.css js/script.js
   ```

4. **Build your HTML structure**:
   - Create a simple header with your name
   - Add a section for your featured content or projects
   - Add a section for your social media links
   - Add a simple footer

5. **Style your page with CSS**:
   - Set up basic styling for your layout
   - Make it responsive for all devices
   - Add any animations or hover effects you want

6. **Enable GitHub Pages**:
   - Push your changes to GitHub
   - Go to your repository settings
   - Enable GitHub Pages from your main branch

This approach gives you complete control over the design and lets you learn as you build!

## 🎨 How to Customize

### Changing Colors
Edit the CSS variables at the top of `style.css`:

```css
:root {
    --bg-color: #0a0a0a; /* Very dark background */
    --card-bg-color: rgba(24, 24, 24, 0.6); /* Semi-transparent for glassmorphism */
    --primary-text: #f0f0f0; /* Brighter primary text */
    --secondary-text: #b0b0b0;
    --accent-color1: #e0405a; /* Pinkish-Red */
    --accent-color2: #c83e7f; /* Purplish-Pink */
    /* other variables... */
}
```

### Adding New Social Links
Copy an existing social link in the HTML and change it:

```html
<li><a href="YOUR_LINK_URL" target="_blank" aria-label="Platform Name">
    <i class="fa-brands fa-icon-name"></i><span>Platform Name</span>
</a></li>
```

### Adding New Content Cards
Copy an existing card and change it:

```html
<div class="card">
    <div class="card-icon"><i class="fa-solid fa-icon-name"></i></div>
    <h3>Card Title</h3>
    <p>Card description text here.</p>
    <a href="YOUR_LINK_URL" target="_blank" class="btn">Button Text <i class="fa-solid fa-arrow-right"></i></a>
</div>
```

## Other Ways to Make a Links Page

If you don't want to use my design, here are some other ways to create your own links page:

- Start from scratch with your own HTML/CSS design using [FreeCodeCamp's tutorials](https://www.freecodecamp.org/learn/2022/responsive-web-design/)
- Use a CSS framework like [Bootstrap](https://getbootstrap.com/docs/5.3/getting-started/introduction/) (has ready-made components)
- Try [Jekyll](https://jekyllrb.com/docs/), which works great with GitHub Pages
- Make a [GitHub profile README](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/about-your-profile) (simpler alternative)

##  Works On

This website works well on:
- Chrome, Firefox and Edge (latest versions)
- iPhone and Android phones and tablets

## Technologies Used in This Project

- [HTML5](https://www.freecodecamp.org/learn/2022/responsive-web-design/) - The structure of the website
- [CSS3](https://www.freecodecamp.org/learn/2022/responsive-web-design/) - The styling, animations, and layout
- [Vanilla JavaScript](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/) - For future interactive features
- [Font Awesome 6](https://fontawesome.com/v6/docs/) - For all the icons used throughout the site
- [Mona Sans Font](https://github.com/github/mona-sans) - The main font used for text
- [CSS Variables](https://www.freecodecamp.org/news/css-variables-explained-with-5-examples/) - For easy color and style changes
- [CSS Animations](https://www.freecodecamp.org/news/a-quick-introduction-to-css-animations-a1655375ec90/) - For fade-in and hover effects
- [Flexbox & Grid](https://www.freecodecamp.org/news/css-flexbox-and-grid-tutorial/) - For responsive layouts
- [GitHub Pages](https://pages.github.com/) - Free hosting for your website

## License

Feel free to use this project for inspiration or as a starting point for your own link-in-bio website. Credit is nice but not required.

## Credits

- [Font Awesome](https://fontawesome.com/) for the icons
- [Mona Sans](https://github.com/github/mona-sans) font by GitHub
- [GitHub Pages](https://pages.github.com/) for the free website hosting

## Helpful Links

- [FreeCodeCamp](https://www.freecodecamp.org/) - Free coding courses and tutorials
- [CSS-Tricks](https://css-tricks.com/) - Great CSS tutorials and examples
- [Font Awesome Icons Search](https://fontawesome.com/icons) - Find icons for your project
- [W3Schools](https://www.w3schools.com/) - Simple web development tutorials
- [Can I Use](https://caniuse.com/) - Check if browsers support certain features

---

Made with Rooibos tea and ❤️
