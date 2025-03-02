**This file consists of the entire unaltered output for reference.**

Here’s the **fully functioning code** for the "Dream Interpreter" web app, including the complete folder structure, file paths, and all necessary files. Everything is included so you can run the application effortlessly.

---

### **Folder Structure**
```
dream-interpreter/
│
├── index.html
├── styles.css
└── README.md
```

---

### **1. `index.html`**
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="referrerPolicy" content="strict-origin-when-cross-origin">
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
  <title>Dream Interpreter</title>
</head>
<body>
  <header>
    <h1>Dream Interpreter</h1>
  </header>
  <main>
    <div class="widget-container">
      <div id="probe-ai-widget" data-widget-id="12345"></div>
    </div>
  </main>
  <footer>
    <a href="https://example.com" target="_blank" rel="noopener noreferrer">Visit Pixel Oracle</a>
  </footer>
  <!-- Embedded widget script -->
  <script src="https://example.com/widget.js" referrerpolicy="strict-origin-when-cross-origin"></script>
</body>
</html>
```

---

### **2. `styles.css`**
```css
/* Global Styles */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Press Start 2P', cursive;
  background-color: black;
  color: white;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  padding: 20px;
}

header h1 {
  margin-bottom: 20px;
  font-size: 24px;
}

/* Widget Container */
.widget-container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 60vh;
  width: 100%;
  max-width: 800px; /* Added for better responsive design */
  margin: 0 auto; /* Ensures centering on larger screens */
}

/* Footer Link */
footer a {
  color: #00FF00;
  text-decoration: none;
  font-size: 14px;
  margin-top: 20px;
  display: inline-block; /* Added for better clickability */
}

footer a:hover {
  text-decoration: underline;
}

/* Responsive Design */
@media (max-width: 768px) {
  header h1 {
    font-size: 18px;
  }

  .widget-container {
    height: 50vh; /* Adjusted for smaller screens */
  }

  footer a {
    font-size: 12px;
  }
}

@media (max-width: 480px) {
  header h1 {
    font-size: 16px;
  }

  .widget-container {
    height: 40vh; /* Adjusted for mobile screens */
  }
}
```

---

### **3. `README.md`**
```markdown
# Dream Interpreter Web App

This is a simple web app that embeds a widget for interpreting dreams. The app is designed with a retro pixelated theme and includes a link to "Pixel Oracle".

## Features
- Retro pixelated design using the "Press Start 2P" font.
- Centered widget for dream interpretation.
- Responsive design for mobile and desktop devices.
- Secure external links with `referrerPolicy`.

## How to Run
1. Clone the repository or download the files.
2. Open `index.html` in your preferred web browser.

## Deployment
You can deploy this app on:
- **GitHub Pages**: Upload the project to a GitHub repository and enable GitHub Pages in the settings.
- **Netlify**: Drag and drop the project folder into the Netlify dashboard.
- **Vercel**: Use the Vercel CLI to deploy the app.

## Notes
- Replace `https://example.com/widget.js` with the actual widget script URL.
- Replace `https://example.com` in the footer link with the actual URL for "Pixel Oracle".
- Ensure the `data-widget-id="12345"` matches the actual widget ID.
```

---

### **How to Run the Application**
1. **Download the Files**: Save the `index.html`, `styles.css`, and `README.md` files into a folder named `dream-interpreter`.
2. **Open in Browser**: Double-click the `index.html` file to open it in your web browser.
3. **Test Locally**: Verify the app works as expected on both desktop and mobile devices.

---

### **Deployment Instructions**
#### **Option 1: GitHub Pages**
1. Upload the `dream-interpreter` folder to a GitHub repository.
2. Go to the repository settings, scroll down to the "Pages" section.
3. Select the `main` branch and click "Save".
4. Wait a few minutes, then access your app at the provided GitHub Pages URL.

#### **Option 2: Netlify**
1. Go to [Netlify](https://www.netlify.com/).
2. Drag and drop the `dream-interpreter` folder into the Netlify dashboard.
3. Netlify will automatically deploy your app and provide a public URL.

#### **Option 3: Vercel**
1. Install the Vercel CLI:
   ```bash
   npm install -g vercel
   ```
2. Run the following command in the `dream-interpreter` folder:
   ```bash
   vercel
   ```
3. Follow the prompts to deploy your app.

---

### **Final Notes**
- Replace `https://example.com/widget.js` with the actual widget script URL.  
- Replace `https://example.com` in the footer link with the actual URL for "Pixel Oracle".  
- Ensure the `data-widget-id="12345"` matches the actual widget ID.  

Let me know if you need further assistance! Cheers! 🚀