# Himanshu Mishra — Personal Website

A minimal academic portfolio website inspired by LaTeX typesetting.

## Files

| File | Description |
|---|---|
| `index.html` | Home page |
| `experience.html` | Research & work experience |
| `projects.html` | Projects |
| `blogs.html` | Blog index |
| `academic_blog.html` | Academic notes / posts |
| `beyond_work.html` | Sports & interests |

## How to deploy on GitHub Pages

1. Create a GitHub repo named `yourusername.github.io`
2. Upload all HTML files to the root of the repo
3. Go to repo Settings → Pages → set source to `main` branch, root folder
4. Your site will be live at `https://yourusername.github.io`

## Profile photo

Replace the `<div class="profile-placeholder">HM</div>` in `index.html` with:

```html
<img src="pfp.jpg" alt="Himanshu Mishra" class="profile-img" />
```

Then upload your photo as `pfp.jpg` to the repo root.

## Adding a blog post

Open `academic_blog.html` and follow the comments inside.  
For math, use `$...$` for inline and `$$...$$` for display — KaTeX renders it automatically.

## Updating projects / experience

Edit the relevant HTML file directly — each entry is clearly commented.
