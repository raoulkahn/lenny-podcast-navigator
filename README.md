# Lenny's Podcast Navigator

A clean, category-based navigation tool for Lenny's Podcast episodes. Built to help Product Managers quickly find relevant episodes for what they're working on right now.

## 🎯 Features

- **5 Main Categories**: AI, Growth, Product-Market Fit, Leadership, Career Development
- **300+ Episodes**: All episodes organized and searchable
- **Rich Metadata**: Guest names, descriptions, view counts, durations
- **Direct Links**: Opens episodes on YouTube in new tabs
- **Mobile Responsive**: Works great on all devices
- **Fast & Clean**: No frameworks, just HTML/CSS/JS

## 📂 Project Structure

```
lenny-navigator/
├── index.html              # Homepage with category cards
├── build-with-ai.html      # AI category page (41 episodes)
├── drive-growth.html       # Growth category page (109 episodes)
├── find-pmf.html          # PMF category page (202 episodes)
├── hire-lead-teams.html   # Leadership category page (134 episodes)
├── advance-career.html    # Career category page (85 episodes)
├── styles.css             # Main stylesheet
├── episodes_data.json     # Parsed episode data
├── parse_episodes.py      # Script to parse episode data
└── generate_pages.py      # Script to generate HTML pages
```

## 🚀 Deploy to GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `lenny-podcast-navigator`
3. Description: "Category-based navigation for Lenny's Podcast episodes"
4. Make it **Public**
5. Click **Create repository**

### Step 2: Upload Files

**Option A: Using GitHub Web Interface**

1. On your new repo page, click **uploading an existing file**
2. Drag these files from the `lenny-navigator` folder:
   - `index.html`
   - `styles.css`
   - `build-with-ai.html`
   - `drive-growth.html`
   - `find-pmf.html`
   - `hire-lead-teams.html`
   - `advance-career.html`
3. Commit message: "Initial commit: Lenny's Podcast Navigator"
4. Click **Commit changes**

**Option B: Using Git Command Line**

```bash
cd /path/to/lenny-navigator

git init
git add index.html styles.css *.html
git commit -m "Initial commit: Lenny's Podcast Navigator"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/lenny-podcast-navigator.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repo **Settings**
2. Click **Pages** in the left sidebar
3. Under **Source**, select **main** branch
4. Click **Save**
5. Wait 1-2 minutes for deployment

### Step 4: Visit Your Site! 🎉

Your site will be live at:
```
https://YOUR_USERNAME.github.io/lenny-podcast-navigator/
```

## 🔄 Updating Episodes (Future)

When new episodes are released:

1. Download latest transcripts from [Lenny's GitHub](https://github.com/lachie83/lennys-podcast-transcripts)
2. Run `python3 parse_episodes.py` to update data
3. Run `python3 generate_pages.py` to regenerate HTML
4. Commit and push changes

## 📝 Customization

### Update Your GitHub Username

In all HTML files, replace:
```html
<a href="https://github.com/yourusername" target="_blank">Ra</a>
```

With your actual GitHub username.

### Update Episode Count Disclaimer

In `index.html`, update the date:
```html
<p class="subtitle">300+ episodes organized by category • Current as of [YOUR DATE]</p>
```

## 🎨 Design Choices

- **Clean & Modern**: No excessive animations or distracting elements
- **Category Colors**: Each category has a distinct accent color
- **Mobile-First**: Responsive grid layout adapts to all screen sizes
- **Fast Loading**: No external dependencies, pure HTML/CSS
- **Accessible**: Semantic HTML, proper contrast ratios

## 📊 Episode Statistics

- **Total Unique Episodes**: 303
- **Total Category Placements**: 571 (episodes can be in multiple categories)
- **Most Popular Category**: Find Product-Market Fit (202 episodes)
- **Episode with Most Views**: [Check the site!]

## 🙏 Credits

- **Podcast**: [Lenny's Podcast](https://www.lennysnewsletter.com/podcast) by Lenny Rachitsky
- **Transcripts**: [GitHub Repository](https://github.com/lachie83/lennys-podcast-transcripts)
- **Built by**: Ra (looking for PM roles!)

## 📄 License

This is an unofficial fan-made tool. All podcast content © Lenny Rachitsky.

---

**Built with ❤️ for Product Managers**
