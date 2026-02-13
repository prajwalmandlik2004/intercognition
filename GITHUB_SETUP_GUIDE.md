# 📚 GitHub Repository Setup Guide - Intercognition

## 🎯 What You Have

All files ready to upload to GitHub:
- README.md
- CITATION.cff
- LICENSE
- CONTRIBUTING.md
- .github/ISSUE_TEMPLATE.md
- .github/PULL_REQUEST_TEMPLATE.md
- docs/index.md

---

## 📋 Step-by-Step Instructions

### Step 1: Create GitHub Account (if you don't have one)

1. Go to https://github.com
2. Click "Sign up"
3. Follow the registration process
4. Verify your email

### Step 2: Create New Repository

1. **Login to GitHub**
2. **Click the "+" icon** in top right corner
3. **Select "New repository"**

### Step 3: Repository Settings

Fill in these details:

**Repository name:** `intercognition`

**Description (optional):**
```
Public reference for the Intercognition concept - Definition and resources for interdisciplinary study
```

**Visibility:**
- ✅ Select **Public** (so everyone can see it)

**Initialize repository:**
- ✅ **CHECK** "Add a README file"
- ✅ **CHECK** "Choose a license" → Select **"Creative Commons Attribution 4.0 International"**
- ⬜ **DON'T CHECK** "Add .gitignore"

**Click "Create repository"**

### Step 4: Upload Your Files

Now you have an empty repository with just README.md and LICENSE.

**Method 1: Web Interface (Easiest)**

1. **In your repository page**, click **"Add file"** → **"Upload files"**

2. **Upload files in this order:**

   **First batch - Root files:**
   - Drag and drop: `CITATION.cff`
   - Drag and drop: `CONTRIBUTING.md`
   - Delete the auto-generated `README.md` and upload your custom one
   - Delete the auto-generated `LICENSE` and upload your custom one

   **Scroll down** and add commit message:
   ```
   Add core documentation files
   ```
   Click **"Commit changes"**

3. **Second batch - Create .github folder:**
   
   - Click **"Add file"** → **"Create new file"**
   - In the filename box, type: `.github/ISSUE_TEMPLATE.md`
   - Paste the content from your `ISSUE_TEMPLATE.md` file
   - Click **"Commit changes"**
   
   - Click **"Add file"** → **"Create new file"** again
   - Type: `.github/PULL_REQUEST_TEMPLATE.md`
   - Paste the content from your `PULL_REQUEST_TEMPLATE.md` file
   - Click **"Commit changes"**

4. **Third batch - Create docs folder:**
   
   - Click **"Add file"** → **"Create new file"**
   - In the filename box, type: `docs/index.md`
   - Paste the content from your `docs/index.md` file
   - Click **"Commit changes"**

**Method 2: Git Command Line (Advanced)**

If you're comfortable with Git:

```bash
# Clone your new repository
git clone https://github.com/YOUR_USERNAME/intercognition.git
cd intercognition

# Copy all your files into this folder
# Then add and commit
git add .
git commit -m "Initial commit with all documentation"
git push origin main
```

---

## 📁 Final Repository Structure

Your repository should look like this:

```
intercognition/
├── README.md
├── CITATION.cff
├── LICENSE
├── CONTRIBUTING.md
├── .github/
│   ├── ISSUE_TEMPLATE.md
│   └── PULL_REQUEST_TEMPLATE.md
└── docs/
    └── index.md
```

---

## ✅ Verification Checklist

After uploading, verify:

- [ ] README.md displays on the main page
- [ ] LICENSE shows "CC BY 4.0"
- [ ] CITATION.cff is visible
- [ ] CONTRIBUTING.md exists
- [ ] .github folder contains both templates
- [ ] docs folder contains index.md

---

## 🌐 Enable GitHub Pages (Optional)

To make `docs/index.md` accessible as a webpage:

1. Go to **Settings** (in your repository)
2. Click **Pages** (in left sidebar)
3. Under "Source", select **"main"** branch
4. Under "Folder", select **"/docs"**
5. Click **Save**

After a few minutes, your docs will be available at:
```
https://YOUR_USERNAME.github.io/intercognition/
```

---

## 🔗 Repository URL

Your repository will be accessible at:
```
https://github.com/YOUR_USERNAME/intercognition
```

Replace `YOUR_USERNAME` with your actual GitHub username.

---

## 📝 Important Notes

### About README.md

Your README includes:
- ✅ Purpose and definitions
- ✅ Soleau reference (evEp-XMzf-Wh4Z-XQ6e, 2026-01-16)
- ✅ Links to official sites
- ✅ CC BY 4.0 license
- ✅ Citation information
- ✅ Contact email

### About CITATION.cff

This file helps others cite your work properly. It includes:
- Author: Barthélemy Gilles
- Date: 2026-01-16
- License: CC-BY-4.0
- URL: https://intercognition.org

When people use GitHub's "Cite this repository" button, they'll get proper citation format automatically!

---

## 🆘 Troubleshooting

### "File already exists"
- Delete the auto-generated file first, then upload yours

### ".github folder not showing"
- Folders starting with `.` are hidden by default
- Click on the folder name in the file list to see contents

### "Can't create folder"
- Use the "Create new file" method
- Type `folder_name/file_name.md` in the filename box
- This creates the folder automatically

---

## 🎉 Next Steps

After setup:

1. **Add repository description:**
   - Click ⚙️ icon next to "About" on main page
   - Add: "Public reference for the Intercognition concept"
   - Add topics: `intercognition`, `cognitive-science`, `ai`, `interdisciplinary`
   - Add website: `https://intercognition.org`

2. **Enable Discussions (optional):**
   - Settings → Features → Check "Discussions"

3. **Share your repository:**
   - Copy the URL: `https://github.com/YOUR_USERNAME/intercognition`
   - Share with collaborators

---

## 📞 Support

- **GitHub Help:** https://docs.github.com
- **Contact:** contact@intercognition.org

---

## ✨ Quick Reference - File Contents

All files are provided in the `github-repo` folder. Simply:

1. Create repository on GitHub
2. Upload files from `github-repo` folder
3. Maintain the folder structure (.github/ and docs/)
4. Done! ✅

Repository URL format: `https://github.com/YOUR_USERNAME/intercognition`
