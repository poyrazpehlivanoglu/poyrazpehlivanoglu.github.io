# poyrazpehlivanoglu.github.io
Computer Engineering student portfolio

## Project Structure

```
poyrazpehlivanoglu.github.io/
├── index.html          # Main portfolio page
├── assets/             # Static assets (images, PDF files, etc.)
│   └── Poyraz_Pehlivanoglu_CV.pdf   # CV/Resume PDF
└── README.md           # This file
```

## How to Add a Folder

Git does not track empty folders, so every folder must contain at least one file.

**Option 1 – GitHub web interface:**
1. Go to your repository on GitHub.
2. Click **Add file → Create new file**.
3. In the filename field, type the folder name followed by `/` and then the file name (e.g. `images/photo.jpg`). GitHub will automatically create the folder.

**Option 2 – Local (command line):**
```bash
mkdir assets          # create the folder
touch assets/.gitkeep # add a placeholder so Git tracks the empty folder
git add assets/.gitkeep
git commit -m "Add assets folder"
git push
```

Once the folder exists you can upload real files (such as your CV PDF) directly through the GitHub web interface or via `git add`.
