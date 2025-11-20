<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>AI Chatbot</title>
  <link rel="stylesheet" href="style.css">
</head>

<body class="theme-dark">

  <!-- Intro Animation -->
  <div class="intro">
    <h1 class="intro-text" id="introText"></h1>
    <h3 class="intro-subtext" id="introName">Made by Nishant Kumar</h3>
  </div>

  <div class="container hidden">
    
    <header>
      <h2>AI Chatbot <span class="header-name">by Nishant prajapati</span></h2>

      <!-- THEME SWITCHER -->
      <select id="themeSelect">
        <option value="theme-dark">Dark</option>
        <option value="theme-light">Light</option>
        <option value="theme-neon">Neon Blue</option>
      </select>
    </header>

    <!-- Camera Preview -->
    <div class="camera-section">
      <video id="camera" autoplay></video>
      <button id="startCamera">📷 Camera On</button>
    </div>

    <!-- Chat Window -->
    <div class="chat-window" id="chatWindow">
      <div class="message bot">Namaste! Main aapka AI Chatbot hoon 😊</div>
    </div>

    <!-- Input Area -->
    <div class="input-area">
      <input type="text" id="userInput" placeholder="Type your message...">
      <button id="micBtn">🎤</button>
      <button id="sendBtn">➤</button>
    </div>

    <!-- Footer -->
    <footer>
      Created by Nishant Kumar
    </footer>

  </div>

  <script src="script.js"></script>
</body>
</html>
