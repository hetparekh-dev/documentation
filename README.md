# 📘 Documentation Site

Welcome to the official documentation site built with **MkDocs** and the **Material for MkDocs** theme.

## ✅ Prerequisites

Make sure you have Python and pip installed:

```bash
python --version  
pip --version
```

## 📦 Installation

Install MkDocs and required packages:

```bash
pip install mkdocs  
pip install mkdocs-material  
pip install click-man  # optional
```

## 🚧 Project Setup

Create a new MkDocs project (if not already created):

```bash
mkdocs new .
```

Check the installed version of MkDocs:

```bash
python -m mkdocs --version
```

## 💻 Local Development Server

Run the local development server:

```bash
mkdocs serve
```

Then open your browser and visit:  
[http://127.0.0.1:8000/](http://127.0.0.1:8000/)

## 📂 Project Structure

```
.
├── docs/
│   ├── index.md          # Home page content
│   └── other-pages.md    # Additional pages
├── mkdocs.yml            # Site configuration
└── README.md             # Project overview
```

## 🚀 Deployment to GitHub Pages

To deploy the documentation to GitHub Pages:

```bash
mkdocs gh-deploy
```

## 🔗 Live Site

[https://hetparekh-dev.github.io/documentation](https://hetparekh-dev.github.io/documentation)

## 📌 Git Commands for Version Control

```bash
git init  
git remote add origin https://github.com/hetparekh-dev/documentation.git  
git add .  
git commit -m "Initial commit"  
git push -u origin master
```

To update only `README.md`:

```bash
git add README.md  
git commit -m "Update README.md"  
git push origin master
```

## 🤝 Contribution Guidelines

1. Fork the repository  
2. Create a feature branch (`git checkout -b feature-xyz`)  
3. Commit your changes (`git commit -m "Add feature"`)  
4. Push the branch (`git push origin feature-xyz`)  
5. Create a Pull Request  

## 📄 License

This project is licensed under the [MIT License](LICENSE).
