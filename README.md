## ⭐ About Me:
Hi, I'm a student at SMKN 2 Surabaya 🎓, majoring in Software Engineering 💻 with a focus on Frontend Development 👨‍💻.  
I'm passionate about creating engaging and user-friendly interfaces ✨, and I'm constantly improving my skills in HTML, CSS, JavaScript, and various frontend frameworks ⚡.  
I'm eager to collaborate on exciting projects and continue learning in the tech world 🌏.

Feel free to explore my repositories and connect with me for potential collaborations! 🤝

---

## 🛠️ Tech Stack:
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Canva](https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Unity](https://img.shields.io/badge/Unity-100000?style=for-the-badge&logo=unity&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)


---

## 🌐 Socials:
[![Discord](https://img.shields.io/badge/Discord-%237289DA.svg?logo=discord&logoColor=white)](https://discordapp.com/users/1144268301611053156)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?logo=instagram&logoColor=white)](https://www.instagram.com/redhiiyy?igsh=eGhyMmZnZDd5Y3lx)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mkhoiruz-z-b0507737a/?trk=opento_sprofile_details)
[![Gmail](https://img.shields.io/badge/Gmail-D14836.svg?logo=gmail&logoColor=white)](mailto:mkhoiruzz21@gmail.com)

---

## 🏆 GitHub Trophies
[![trophy](https://github-profile-trophy.vercel.app/?username=mkhoiruzzz&theme=onedark&no-frame=false&no-bg=false&margin-w=15&row=2&column=5)](https://github.com/ryo-ma/github-profile-trophy)

---

## ✍️ Random Dev Quote
![Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=radical)

---

## 📊 Top Contributed Repo
![Top Contributed Repo](https://github-contributor-stats.vercel.app/api?username=mkhoiruzzz&limit=5&theme=dark&combine_all_yearly_contributions=true)



<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Pacman Animation for GitHub Profile</title>
    <style>
        body {
            background: #0d1117;
            color: #c9d1d9;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 20px;
            min-height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
        }

        .container {
            background: #161b22;
            border: 1px solid #30363d;
            border-radius: 8px;
            padding: 30px;
            margin: 20px 0;
            max-width: 800px;
            width: 100%;
        }

        h1 {
            text-align: center;
            color: #58a6ff;
            margin-bottom: 30px;
        }

        .demo-section {
            margin: 30px 0;
            text-align: center;
        }

        /* Pacman Animation Styles */
        .pacman-container {
            display: flex;
            align-items: center;
            justify-content: center;
            height: 80px;
            background: #0d1117;
            border-radius: 8px;
            padding: 20px;
            margin: 20px 0;
            overflow: hidden;
            position: relative;
            border: 1px solid #21262d;
        }

        .pacman {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: #ffd700;
            position: relative;
            animation: movePacman 4s linear infinite;
        }

        .pacman::before {
            content: '';
            position: absolute;
            width: 0;
            height: 0;
            border: 20px solid #ffd700;
            border-right-color: transparent;
            border-top-color: transparent;
            border-radius: 50%;
            animation: chomp 0.5s ease-in-out infinite;
        }

        .dots {
            display: flex;
            gap: 30px;
            position: absolute;
            left: 100px;
            top: 50%;
            transform: translateY(-50%);
        }

        .dot {
            width: 8px;
            height: 8px;
            background: #58a6ff;
            border-radius: 50%;
            animation: disappear 4s linear infinite;
        }

        .dot:nth-child(2) {
            animation-delay: 0.5s;
        }

        .dot:nth-child(3) {
            animation-delay: 1s;
        }

        .dot:nth-child(4) {
            animation-delay: 1.5s;
        }

        .dot:nth-child(5) {
            animation-delay: 2s;
        }

        @keyframes movePacman {
            0% {
                transform: translateX(-50px);
            }
            100% {
                transform: translateX(300px);
            }
        }

        @keyframes chomp {
            0%, 100% {
                transform: rotate(0deg);
            }
            50% {
                transform: rotate(-45deg);
            }
        }

        @keyframes disappear {
            0%, 12.5% {
                opacity: 1;
                transform: scale(1);
            }
            13% {
                opacity: 0;
                transform: scale(0.5);
            }
            100% {
                opacity: 0;
                transform: scale(0.5);
            }
        }

        /* Alternative Vertical Pacman */
        .pacman-vertical {
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: #ffd700;
            position: relative;
            animation: movePacmanVertical 3s linear infinite;
        }

        .pacman-vertical::before {
            content: '';
            position: absolute;
            width: 0;
            height: 0;
            border: 20px solid #ffd700;
            border-bottom-color: transparent;
            border-left-color: transparent;
            border-radius: 50%;
            animation: chompVertical 0.4s ease-in-out infinite;
        }

        .pacman-container-vertical {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: flex-start;
            width: 80px;
            height: 300px;
            background: #0d1117;
            border-radius: 8px;
            padding: 20px;
            margin: 20px auto;
            overflow: hidden;
            position: relative;
            border: 1px solid #21262d;
        }

        .dots-vertical {
            display: flex;
            flex-direction: column;
            gap: 20px;
            position: absolute;
            top: 80px;
            left: 50%;
            transform: translateX(-50%);
        }

        .dot-vertical {
            width: 8px;
            height: 8px;
            background: #58a6ff;
            border-radius: 50%;
            animation: disappearVertical 3s linear infinite;
        }

        .dot-vertical:nth-child(2) {
            animation-delay: 0.4s;
        }

        .dot-vertical:nth-child(3) {
            animation-delay: 0.8s;
        }

        .dot-vertical:nth-child(4) {
            animation-delay: 1.2s;
        }

        @keyframes movePacmanVertical {
            0% {
                transform: translateY(-30px);
            }
            100% {
                transform: translateY(250px);
            }
        }

        @keyframes chompVertical {
            0%, 100% {
                transform: rotate(90deg);
            }
            50% {
                transform: rotate(45deg);
            }
        }

        @keyframes disappearVertical {
            0%, 13% {
                opacity: 1;
                transform: scale(1);
            }
            14% {
                opacity: 0;
                transform: scale(0.5);
            }
            100% {
                opacity: 0;
                transform: scale(0.5);
            }
        }

        /* Code blocks */
        .code-block {
            background: #0d1117;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 16px;
            margin: 20px 0;
            overflow-x: auto;
            font-family: 'Courier New', monospace;
            font-size: 14px;
            line-height: 1.5;
        }

        .code-block pre {
            margin: 0;
            white-space: pre-wrap;
        }

        .instructions {
            background: #1c2128;
            border-left: 4px solid #58a6ff;
            padding: 16px;
            margin: 20px 0;
            border-radius: 0 6px 6px 0;
        }

        .demo-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 20px;
            margin: 30px 0;
        }

        .demo-item {
            text-align: center;
        }

        .demo-item h3 {
            color: #f0f6fc;
            margin-bottom: 15px;
        }

        .copy-btn {
            background: #238636;
            color: white;
            border: none;
            padding: 8px 16px;
            border-radius: 6px;
            cursor: pointer;
            font-size: 14px;
            margin-top: 10px;
            transition: background-color 0.2s;
        }

        .copy-btn:hover {
            background: #2ea043;
        }

        .copy-btn:active {
            background: #1a7f37;
        }

        @media (max-width: 768px) {
            .demo-grid {
                grid-template-columns: 1fr;
            }
            
            .pacman-container {
                overflow-x: auto;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🎮 Animasi Pacman untuk Profil GitHub</h1>
        
        <div class="instructions">
            <h3>📋 Cara Penggunaan:</h3>
            <p>1. Salin kode SVG atau HTML di bawah ini</p>
            <p>2. Tambahkan ke README.md profil GitHub Anda</p>
            <p>3. Commit dan push perubahan</p>
            <p>4. Animasi akan muncul di profil GitHub Anda!</p>
        </div>

        <div class="demo-grid">
            <div class="demo-item">
                <h3>Horizontal Pacman</h3>
                <div class="pacman-container">
                    <div class="pacman"></div>
                    <div class="dots">
                        <div class="dot"></div>
                        <div class="dot"></div>
                        <div class="dot"></div>
                        <div class="dot"></div>
                        <div class="dot"></div>
                    </div>
                </div>
            </div>

            <div class="demo-item">
                <h3>Vertical Pacman</h3>
                <div class="pacman-container-vertical">
                    <div class="pacman-vertical"></div>
                    <div class="dots-vertical">
                        <div class="dot-vertical"></div>
                        <div class="dot-vertical"></div>
                        <div class="dot-vertical"></div>
                        <div class="dot-vertical"></div>
                    </div>
                </div>
            </div>
        </div>

        <div class="demo-section">
            <h2>🎯 SVG Animasi (Horizontal) - Siap untuk GitHub!</h2>
            <div class="code-block">
                <pre id="svg-code">&lt;div align="center"&gt;
  &lt;img src="https://raw.githubusercontent.com/mkhoiruzzz/mkhoiruzzz/main/pacman.svg" width="400" height="100"/&gt;
&lt;/div&gt;

&lt;!-- Atau gunakan SVG langsung: --&gt;
&lt;div align="center"&gt;
&lt;svg width="400" height="100" xmlns="http://www.w3.org/2000/svg"&gt;
  &lt;defs&gt;
    &lt;style&gt;
      .pacman {
        animation: move 4s linear infinite;
      }
      .pacman-mouth {
        animation: chomp 0.5s ease-in-out infinite;
      }
      .dot {
        animation: disappear 4s linear infinite;
      }
      .dot:nth-child(2) { animation-delay: 0.5s; }
      .dot:nth-child(3) { animation-delay: 1s; }
      .dot:nth-child(4) { animation-delay: 1.5s; }
      .dot:nth-child(5) { animation-delay: 2s; }
      
      @keyframes move {
        0% { transform: translateX(0); }
        100% { transform: translateX(300px); }
      }
      @keyframes chomp {
        0%, 100% { d: path("M20,50 L20,20 A15,15 0 1,1 20,80 Z"); }
        50% { d: path("M20,50 L35,35 A15,15 0 1,1 35,65 Z"); }
      }
      @keyframes disappear {
        0%, 12.5% { opacity: 1; }
        13%, 100% { opacity: 0; }
      }
    &lt;/style&gt;
  &lt;/defs&gt;
  
  &lt;g class="pacman"&gt;
    &lt;circle cx="20" cy="50" r="15" fill="#FFD700"/&gt;
    &lt;path class="pacman-mouth" d="M20,50 L20,20 A15,15 0 1,1 20,80 Z" fill="#0D1117"/&gt;
  &lt;/g&gt;
  
  &lt;circle class="dot" cx="80" cy="50" r="4" fill="#58A6FF"/&gt;
  &lt;circle class="dot" cx="120" cy="50" r="4" fill="#58A6FF"/&gt;
  &lt;circle class="dot" cx="160" cy="50" r="4" fill="#58A6FF"/&gt;
  &lt;circle class="dot" cx="200" cy="50" r="4" fill="#58A6FF"/&gt;
  &lt;circle class="dot" cx="240" cy="50" r="4" fill="#58A6FF"/&gt;
&lt;/svg&gt;
&lt;/div&gt;</pre>
            </div>
            <button class="copy-btn" onclick="copyToClipboard('svg-code')">📋 Salin Kode SVG</button>
        </div>

        <div class="demo-section">
            <h2>🚀 Versi CSS untuk HTML (Advanced)</h2>
            <div class="code-block">
                <pre id="css-code">&lt;div align="center"&gt;
  &lt;div style="display: inline-block; background: #0d1117; padding: 20px; border-radius: 8px;"&gt;
    &lt;div style="
      width: 40px; 
      height: 40px; 
      border-radius: 50%; 
      background: #ffd700;
      position: relative;
      animation: pacman-move 4s linear infinite;
      display: inline-block;
    "&gt;
      &lt;div style="
        position: absolute;
        width: 0;
        height: 0;
        border: 20px solid #ffd700;
        border-right-color: transparent;
        border-top-color: transparent;
        animation: pacman-chomp 0.5s ease-in-out infinite;
      "&gt;&lt;/div&gt;
    &lt;/div&gt;
    &lt;span style="margin-left: 20px; color: #58a6ff; font-size: 24px;"&gt;● ● ● ● ●&lt;/span&gt;
  &lt;/div&gt;
&lt;/div&gt;

&lt;style&gt;
@keyframes pacman-move {
  0% { transform: translateX(-20px); }
  100% { transform: translateX(100px); }
}
@keyframes pacman-chomp {
  0%, 100% { transform: rotate(0deg); }
  50% { transform: rotate(-45deg); }
}
&lt;/style&gt;</pre>
            </div>
            <button class="copy-btn" onclick="copyToClipboard('css-code')">📋 Salin Kode CSS</button>
        </div>

        <div class="demo-section">
            <h2>🎨 Versi Sederhana dengan Emoji</h2>
            <div class="code-block">
                <pre id="emoji-code">&lt;div align="center"&gt;
  &lt;h2&gt;
    &lt;img src="https://media.giphy.com/media/3oKIPnAiaMCws8nOsE/giphy.gif" width="30"&gt;
    Selamat datang di profil saya! 
    &lt;img src="https://media.giphy.com/media/3oKIPnAiaMCws8nOsE/giphy.gif" width="30"&gt;
  &lt;/h2&gt;
&lt;/div&gt;

&lt;!-- Atau dengan emoji sederhana --&gt;
&lt;div align="center"&gt;
  &lt;h2&gt;🟡 ← ● ● ● ● ● Catching bugs in my code!&lt;/h2&gt;
&lt;/div&gt;</pre>
            </div>
            <button class="copy-btn" onclick="copyToClipboard('emoji-code')">📋 Salin Kode Emoji</button>
        </div>

        <div class="instructions">
            <h3>💡 Tips Tambahan:</h3>
            <p>• Untuk hasil terbaik, gunakan versi SVG karena lebih ringan dan kompatibel</p>
            <p>• Jika menggunakan file SVG terpisah, upload ke repository dengan nama "pacman.svg"</p>
            <p>• Sesuaikan warna dengan tema profil GitHub Anda</p>
            <p>• Kombinasikan dengan elemen lain seperti typing animation atau stats</p>
        </div>
    </div>

    <script>
        function copyToClipboard(elementId) {
            const element = document.getElementById(elementId);
            const text = element.textContent;
            
            if (navigator.clipboard) {
                navigator.clipboard.writeText(text).then(function() {
                    showCopySuccess();
                });
            } else {
                // Fallback for older browsers
                const textArea = document.createElement('textarea');
                textArea.value = text;
                document.body.appendChild(textArea);
                textArea.select();
                document.execCommand('copy');
                document.body.removeChild(textArea);
                showCopySuccess();
            }
        }

        function showCopySuccess() {
            const originalText = event.target.textContent;
            event.target.textContent = '✅ Tersalin!';
            event.target.style.background = '#2ea043';
            
            setTimeout(() => {
                event.target.textContent = originalText;
                event.target.style.background = '#238636';
            }, 2000);
        }
    </script>
</body>
</html>
