<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Khalil Greene - Portfolio</title>
  <style>
    :root {
      --gold: #ffcc00;
      --black: #0a0a0a;
      --gray: #f5f5f5;
    }

    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: var(--black);
      color: var(--gray);
      margin: 0;
      line-height: 1.6;
      scroll-behavior: smooth;
    }

    header {
      background: linear-gradient(90deg, #000, #1a1a1a);
      padding: 20px;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
      border-bottom: 2px solid var(--gold);
    }

    header h1 {
      color: var(--gold);
      margin: 0;
      font-size: 1.8rem;
    }

    nav {
      margin-top: 10px;
    }

    nav a {
      color: var(--gray);
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
      transition: color 0.3s ease, border-bottom 0.3s ease;
      border-bottom: 2px solid transparent;
    }

    nav a:hover {
      color: var(--gold);
      border-bottom: 2px solid var(--gold);
    }

    section {
      padding: 60px 20px;
      max-width: 900px;
      margin: 50px auto;
      background-color: #111;
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(255, 204, 0, 0.1);
    }

    h2 {
      color: var(--gold);
      text-align: center;
      margin-bottom: 20px;
      font-size: 1.6rem;
    }

    img.profile {
      width: 270px;
      height: 270px;
      border-radius: 20px;
      border: 5px solid var(--gold);
      display: block;
      margin: 24px auto;
      object-fit: cover;
      object-position: top center;
      filter: grayscale(15%) brightness(95%);
      transition: transform 0.5s ease, filter 0.5s ease;
    }

    img.profile:hover {
      filter: grayscale(0%) brightness(110%);
      transform: scale(1.05);
    }

    @media (max-width: 600px) {
      img.profile {
        width: 200px;
        height: 200px;
      }
    }

    .fade-in {
      opacity: 0;
      transform: translateY(20px);
      animation: fadeIn 1.5s forwards;
    }

    @keyframes fadeIn {
      to { opacity: 1; transform: translateY(0); }
    }

    button {
      display: block;
      margin: 30px auto;
      padding: 12px 25px;
      border: none;
      background: var(--gold);
      color: #111;
      font-size: 1rem;
      font-weight: bold;
      border-radius: 25px;
      cursor: pointer;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    button:hover {
      transform: scale(1.1);
      box-shadow: 0 0 15px var(--gold);
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #000;
      color: #888;
      border-top: 2px solid var(--gold);
      margin-top: 50px;
      font-size: 0.9rem;
    }

    /* Chatbot Styles */
    #chatbot {
      position: fixed;
      bottom: 20px;
      right: 20px;
      width: 300px;
      max-height: 400px;
      background-color: #111;
      border: 2px solid var(--gold);
      border-radius: 10px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      font-size: 0.9rem;
      z-index: 2000;
    }

    #chatbot-header {
      background-color: var(--gold);
      color: #111;
      padding: 10px;
      text-align: center;
      font-weight: bold;
      cursor: pointer;
    }

    #chatbot-messages {
      flex: 1;
      padding: 10px;
      overflow-y: auto;
      background-color: #222;
    }

    .message {
      margin-bottom: 10px;
      padding: 8px;
      border-radius: 6px;
    }

    .user-message {
      background-color: #333;
      text-align: right;
    }

    .bot-message {
      background-color: var(--gold);
      color: #111;
      text-align: left;
    }

    #chatbot-input {
      display: flex;
      border-top: 1px solid var(--gold);
    }

    #chatbot-input input {
      flex: 1;
      padding: 8px;
      border: none;
      background-color: #111;
      color: var(--gray);
    }

    #chatbot-input button {
      padding: 8px 12px;
      border: none;
      background-color: var(--gold);
      color: #111;
      cursor: pointer;
    }
  </style>
</head>

<body>

<header>
  <h1>Khalil Greene - Portfolio & Resume</h1>
  <nav>
    <a href="#home">Home</a>
    <a href="#journey">Journey</a>
    <a href="#projects">Projects</a>
    <a href="#resume">Resume</a>
  </nav>
</header>

<!-- Home Section -->
<section id="home" class="fade-in">
  <h2>Welcome</h2>
  <img src="https://codehs.com/uploads/8510fd6fedea07cbb99ef136282c1450" class="profile" alt="Khalil Greene Photo">
  <p>Hello! I'm <strong>Khalil Greene</strong>, a graduating senior Computer Technology major at <strong>Bowie State University</strong>. 
  My journey has been defined by perseverance, leadership, and innovation, along with an understanding of my CTEC (Computer Technology) Track. 
  This portfolio highlights my academic growth, technical experience, and professional ambitions.</p>
</section>

<!-- Journey Section -->
<section id="journey" class="fade-in">
  <h2>Academic Journey</h2>
  <p>Throughout my studies at Bowie State University, I've focused on developing skills in networking, cybersecurity, and database management. Along with experience at a couple companies such as Fico and Carahsoft. Which can be later talked about under the resume portion. 
  These experiences have shaped my passion for data analytics and systems engineering. I strive to use technology to solve problems and create efficient, secure solutions.</p>
</section>

<!-- Projects Section -->
<section id="projects" class="fade-in">
  <h2>My Project</h2>
  <p>Check out my final project:</p>
  <a href="file:///C:/Users/princ/OneDrive/Documents/426CTECProjectFinal.pdf" target="_blank" style="color: var(--gold); text-decoration: underline;">426CTEC Project Final PDF</a>
</section>

<!-- Resume Section -->
<section id="resume" class="fade-in">
  <h2>My Resume</h2>
  <p>Scan the QR code below or click the button to view and download my professional resume.</p>

  <div style="text-align:center;">
    <a href="Appiah,Prince Resume 2025 .pdf" target="_blank">
      <img src="https://api.qrserver.com/v1/create-qr-code/?data=Appiah,Prince%20Resume%202025%20.pdf&size=200x200" alt="Resume QR Code" style="border: 4px solid var(--gold); border-radius: 12px;">
    </a>
  </div>

  <button onclick="window.open('Appiah,Prince Resume 2025 .pdf', '_blank')">View / Download Resume</button>
</section>

<footer>
  <p>© 2025 Prince Appiah | </p>
</footer>

<!-- Chatbot -->
<div id="chatbot">
  <div id="chatbot-header">Chat with Me</div>
  <div id="chatbot-messages"></div>
  <div id="chatbot-input">
    <input type="text" id="userInput" placeholder="Ask me something...">
    <button onclick="sendMessage()">Send</button>
  </div>
</div>

<script>
  // Fade-in on scroll
  const faders = document.querySelectorAll('.fade-in');
  const appearOptions = { threshold: 0.2, rootMargin: "0px 0px -50px 0px" };
  const appearOnScroll = new IntersectionObserver(function(entries, observer) {
    entries.forEach(entry => {
      if (!entry.isIntersecting) return;
      entry.target.style.opacity = 1;
      entry.target.style.transform = 'translateY(0)';
      observer.unobserve(entry.target);
    });
  }, appearOptions);

  faders.forEach(fader => appearOnScroll.observe(fader));

  // Chatbot functionality
  const chatbotMessages = document.getElementById("chatbot-messages");
  const chatbotHeader = document.getElementById("chatbot-header");
  let chatbotOpen = true;

  chatbotHeader.addEventListener("click", () => {
    chatbotOpen = !chatbotOpen;
    document.getElementById("chatbot").style.height = chatbotOpen ? "400px" : "40px";
  });

  function sendMessage() {
    const userInput = document.getElementById("userInput").value.trim();
    if (!userInput) return;

    addMessage(userInput, "user-message");
    document.getElementById("userInput").value = "";

    setTimeout(() => {
      const botReply = getBotReply(userInput);
      addMessage(botReply, "bot-message");
      chatbotMessages.scrollTop = chatbotMessages.scrollHeight;
    }, 500);
  }

  function addMessage(text, className) {
    const msg = document.createElement("div");
    msg.className = "message " + className;
    msg.textContent = text;
    chatbotMessages.appendChild(msg);
  }

  function getBotReply(input) {
    const question = input.toLowerCase();
    if (question.includes("skills")) return "I specialize in networking, cybersecurity, data analytics, and database management.";
    if (question.includes("projects")) return "You can view my final project for CTEC 426 in the Projects section by clicking the PDF link.";
    if (question.includes("experience")) return "I have hands-on experience in system administration, coding, and data management through my coursework and projects. Which also can be further explained in my resume";
    if (question.includes("education")) return "I am a senior Computer Technology major with a concentration in Data Science and Data Admin at Bowie State University.";
    if (question.includes("resume")) return "You can view and download my resume in the Resume section.";
    return "Sorry, I don't understand that. Try asking about my skills, projects, experience, education, or resume.";
  }
</script>

</body>
</html>

