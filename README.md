# 📘 Adocs - Static Docs Template

Adocs is a modern and customizable static documentation site built with **VitePress**. It is designed for developers and teams to create clean, user-friendly documentation with ease.

## Adocs  
![Adocs Thumbnail](https://github.com/sharryXheisenberg/adocs/blob/main/adocs.png)  
---

## 📌 Features
- **⚡ Lightning Fast** – Powered by **VitePress** for instant load times.
- **🎨 Beautiful UI** – Minimalistic design with **Markdown-powered pages**.
- **📚 Sidebar Navigation** – Auto-generated sidebar for better readability.
- **🌓 Light & Dark Mode** – Seamless theme switching.
- **📖 Customizable** – Modify navigation, layout, and styles easily.
- **🔗 Social Links** – GitHub, Discord, Twitter integration.

---

## 🛠 **Installation & Development**
Follow these steps to **clone, install, and run** the project locally.

### 1️⃣ Clone the Repository
``` bash
git clone https://github.com/sharryXheisenberg/adocs.git
```
``` bash
cd adocs
```

### 2️⃣Install Dependencies
``` bash
npm install
```

### 3️⃣ Start Development Server
``` bash
npm run docs:dev
```
- Open  http://localhost:5173/ to see the docs live.


## 📖 Project Structure
``` bash
adocs/
├── .vitepress/      
│   ├── config.js    
│   ├── theme/       
├── docs/            
│   ├── index.md     
│   ├── guide.md     
│   ├── about.md     
│   ├── contact.md   
│   ├── configs.md       
├── public/          
├── package.json     
└── README.md        
```

## 📘 Guide
- Here’s a quick guide on how to use Adocs.

## 📂 Adding New Pages
- To create a new documentation page, add a .md file inside the /docs/ directory like an example
  ``` bash
  ---
  title: New Page
  ---
  # New Page
  Welcome to the new page of Adocs!
  ```
## 📝 Editing Sidebar
``` bash
sidebar: [
  { text: "Guide", link: "/guide" },
  { text: "Configs", link: "/configs" },
]
```

## 🎨 Customizing the Theme
- You can override styles inside theme/ folder.
  ``` bash
  :root {
  --vp-c-brand: #42b983; /*your choosen color*/
  }
  ```

  
## 📜License
This project is licensed under the [MIT License](LICENSE).

## 🤝 Contributing
I welcome all contributions! Feel free to open issues or submit pull requests on [Github issues](https://github.com/sharryXheisenberg/adocs/pulls).

## Acknowledgements

- [Vite](https://vitejs.dev/)
- [VitePress](https://vitepress.dev/)
  

  




