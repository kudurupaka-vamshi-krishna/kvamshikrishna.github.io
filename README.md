# Academic & Research Website — Dr. K. Vamshi Krishna

This repository contains a modular, data-driven personal academic website built specifically for **GitHub Pages** (Jekyll / Static Site Generator) and **Vercel**.

## 📁 Project Directory Structure

```
kvamshikrishna.github.io/
├── _config.yml              # Site metadata (name, emails, institution)
├── _data/                   # All research data stored in YAML format
│   ├── author.yml           # Biography, affiliations, core interests
│   ├── education.yml        # Ph.D., M.Tech, B.Tech degrees
│   ├── publications.yml     # Peer-reviewed journal articles, conference papers, DOIs
│   ├── patents.yml          # Intellectual property & patent filings
│   ├── projects.yml         # Funded research projects & grant agency details
│   ├── skills.yml           # Languages, simulation software, IoT hardware, models
│   ├── awards.yml           # Travel grants, fellowships, scholarships
│   └── navigation.yml       # Navbar menu tabs
├── _layouts/                # HTML layout templates
│   └── default.html         # Base template with Tailwind CSS & FontAwesome
├── _includes/               # Shared components
├── index.html               # Home / Bio page
├── research/index.html      # Research Projects & Patents tab
├── publications/index.html  # Publications & Conference Talks tab
├── skills/index.html        # Skills & Methodologies tab
├── experience/index.html    # Education & Work History tab
├── awards/index.html        # Honors, Fellowships & Grants tab
├── contact/index.html       # Contact Information & Form tab
└── assets/                  # Downloadable assets (PDFs, images)
```

## 🚀 How to Host & Populate for Any Institute or Company

### 1. Initialize Git & Push to GitHub
```bash
git init
git add .
git commit -m "Initial commit of academic research website"
git branch -M main
git remote add origin https://github.com/<your-username>/kvamshikrishna.github.io.git
git push -u origin main
```

### 2. Enable GitHub Pages
1. Go to your repository on GitHub: `https://github.com/<your-username>/kvamshikrishna.github.io`
2. Navigate to **Settings > Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Select `main` branch and `/ (root)` folder, then click **Save**.
5. Your website will be automatically deployed at `https://<your-username>.github.io`.

### 3. Deploying to Vercel (Alternative)
1. Log into [Vercel](https://vercel.com) using your GitHub account.
2. Click **Add New > Project** and import your `kvamshikrishna.github.io` repository.
3. Click **Deploy**. Any future `git push` to your GitHub repo will automatically update your site.

### 4. Updating Content When Joining a New Institute / Company
Whenever you join a new institute, publish new papers, or receive new grants:
- **Change Affiliation / Contact:** Edit `_config.yml` and `_data/author.yml`.
- **Add New Publications / DOIs:** Edit `_data/publications.yml`.
- **Add New Patents or Projects:** Edit `_data/patents.yml` or `_data/projects.yml`.
- **Commit changes:** `git commit -am "Update affiliation" && git push`
