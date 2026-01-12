# Personal Academic Website

A clean, professional website for showcasing your research, publications, and CV.

## Setup Instructions

### 1. Create GitHub Repository
1. Go to [GitHub](https://github.com) and sign in (or create an account)
2. Click the "+" icon in the top right and select "New repository"
3. Name it: `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
4. Make it **Public**
5. Check "Add a README file"
6. Click "Create repository"

### 2. Upload Your Website Files
1. In your new repository, click "Add file" → "Upload files"
2. Upload these files:
   - `index.html`
   - `style.css`
   - Your CV as `cv.pdf` (optional but recommended)
   - A professional photo of yourself (optional)
3. Click "Commit changes"

### 3. Enable GitHub Pages
1. In your repository, go to "Settings"
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Under "Branch", select "main" and "/(root)"
5. Click "Save"

Your site will be live at `https://yourusername.github.io` in a few minutes!

## Customization Checklist

### Essential Updates (Do These First!)
- [ ] Replace `[Your Last Name]` with your actual last name throughout `index.html`
- [ ] Update email address in the Contact section
- [ ] Add your GitHub username link
- [ ] Add your LinkedIn profile link (if you have one)
- [ ] Update the page title in the `<title>` tag

### Content to Add
- [ ] Add a professional photo (replace the placeholder)
- [ ] Add your publications from Montclair State University
- [ ] Upload your CV as `cv.pdf`
- [ ] Customize the "About Me" section with your own words
- [ ] Update the "Current Research" section with specifics about your thesis
- [ ] Add any additional skills or techniques you want to highlight

### Optional Enhancements
- [ ] Add links to your research posters or presentations
- [ ] Create a blog section (if desired)
- [ ] Add a Google Scholar profile link
- [ ] Include any awards or honors you've received

## Adding Your Photo

1. Save your photo as `profile.jpg` or `profile.png`
2. Upload it to your GitHub repository
3. In `index.html`, replace this section:
```html
<div class="placeholder-image">
    <p>Your Photo Here</p>
</div>
```

With:
```html
<img src="profile.jpg" alt="Madeline [Your Last Name]" style="width: 250px; height: 250px; border-radius: 50%; object-fit: cover;">
```

## Updating Your Site

Anytime you want to make changes:
1. Edit the files on your computer
2. Go to your repository on GitHub
3. Click on the file you want to update
4. Click the pencil icon to edit
5. Make your changes
6. Click "Commit changes"

Changes will appear on your live site within a few minutes!

## Color Scheme

The current color scheme uses:
- Primary: Purple gradient (#667eea to #764ba2)
- Accent: Dark blue (#2c5282)
- Background: White and light gray (#f7fafc)

To change colors, edit the hex codes in `style.css`.

## Need Help?

- GitHub Pages documentation: https://pages.github.com/
- Markdown guide: https://guides.github.com/features/mastering-markdown/
- HTML/CSS tutorials: https://www.w3schools.com/

## Tips for Academic Websites

- Keep it professional but personable
- Update regularly with new publications and projects
- Make sure your CV is current
- Use high-quality images
- Test all links before sharing
- Share your website on your email signature, CV, and LinkedIn!
