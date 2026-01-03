<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Spider-Man Wallpapers</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <nav>
    <h1>🕷️ Spider-Man Wallpapers</h1>
  </nav>

  <section class="hero">
    <h2>Cool • Aesthetic • Cinematic</h2>
    <p>Download high-quality Spider-Man wallpapers</p>
  </section>

  <section class="gallery">
    <img src="https://4kwallpapers.com/images/walls/thumbs_3t/8652.jpg"openImg(this.src)">
   <img src="https://i.pinimg.com/736x/10/17/19/1017190716c7e531216d9b78cfcbf748.jpg" onclick="openImg(this.src)">   
    <img src="https://i.pinimg.com/736x/b3/b1/b1/b3b1b155bb7e4263a5401e20e7c9d942.jpg" onclick="openImg(this.src)">
  </section>

  <!-- Fullscreen Preview -->
  <div id="preview">
    <span onclick="closeImg()">✖</span>
    <img id="previewImg">
  </div>

  <footer>
    <p>Fan-made Spider-Man wallpaper site</p>
  </footer>

  <script src="script.js"></script>
</body>
</html>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}

body {
  background: radial-gradient(circle at top, #0b0b2a, #000);
  color: white;
}

nav {
  padding: 20px;
  text-align: center;
  background: rgba(0,0,0,0.6);
}

nav h1 {
  color: #ff2d2d;
}

.hero {
  text-align: center;
  padding: 50px 20px;
}

.hero h2 {
  font-size: 2rem;
}

.hero p {
  opacity: 0.8;
  margin-top: 10px;
}

.gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
  padding: 30px;
}

.gallery img {
  width: 100%;
  border-radius: 15px;
  cursor: pointer;
  transition: transform 0.3s, box-shadow 0.3s;
}

.gallery img:hover {
  transform: scale(1.05);
  box-shadow: 0 10px 30px rgba(255,0,0,0.4);
}

/* Preview */
#preview {
  position: fixed;
  inset: 0;
  background: rgba(0,0,0,0.9);
  display: none;
  align-items: center;
  justify-content: center;
  z-index: 10;
}

#preview img {
  max-width: 90%;
  max-height: 90%;
  border-radius: 10px;
}

#preview span {
  position: absolute;
  top: 20px;
  right: 30px;
  font-size: 2rem;
  cursor: pointer;
}

footer {
  text-align: center;
  padding: 20px;
  opacity: 0.6;
}
function openImg(src) {
  document.getElementById("preview").style.display = "flex";
  document.getElementById("previewImg").src = src;
}

function closeImg() {
  document.getElementById("preview").style.display = "none";
}
