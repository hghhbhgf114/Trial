# NEXUS AI BOT

<div align="center">

<h1>
  <span id="auto-type-title"></span>
</h1>

<br>

<!-- Big, Unique, Live-Auto-Typing Buttons Section -->

<div id="buttons-section" style="display: flex; flex-direction: column; align-items: center; gap: 1.5rem; margin-top: 2rem;">

  <!-- Fork the Repo -->
  <a href="https://github.com/Pkdriller/NEXUS-AI/fork" target="_blank" style="text-decoration: none;">
    <button class="nexus-button" id="fork-btn">🍴 Fork this Repo</button>
  </a>

  <!-- Get Session -->
  <a href="https://nexus-ai-pairing-website.vercel.app/" target="_blank" style="text-decoration: none;">
    <button class="nexus-button" id="session-btn">🔑 Get Session</button>
  </a>

  <!-- Follow on GitHub -->
  <a href="https://github.com/Pkdriller" target="_blank" style="text-decoration: none;">
    <button class="nexus-button" id="github-follow-btn">⭐ Follow Me on GitHub</button>
  </a>

  <!-- Follow WhatsApp Channel -->
  <a href="https://whatsapp.com/channel/0029VaB1rUIEzg1l9nQpMx3P" target="_blank" style="text-decoration: none;">
    <button class="nexus-button" id="whatsapp-btn">💬 Follow WhatsApp Channel</button>
  </a>

  <!-- Deploy on Heroku -->
  <a href="https://heroku.com/deploy?template=https://github.com/Pkdriller/NEXUS-AI" target="_blank" style="text-decoration: none;">
    <button class="nexus-button" id="heroku-btn">🚀 Deploy on Heroku</button>
  </a>

  <!-- Deploy on Render -->
  <a href="https://render.com/deploy?repo=https://github.com/Pkdriller/NEXUS-AI" target="_blank" style="text-decoration: none;">
    <button class="nexus-button" id="render-btn">🌐 Deploy on Render</button>
  </a>

  <!-- Deploy on Railway -->
  <a href="https://railway.app/new/template/JJvLcf" target="_blank" style="text-decoration: none;">
    <button class="nexus-button" id="railway-btn">⚡ Deploy on Railway</button>
  </a>

  <!-- Report Error -->
  <a href="https://github.com/Pkdriller/NEXUS-AI/issues/new?labels=bug&template=bug_report.md" target="_blank" style="text-decoration: none;">
    <button class="nexus-button" id="report-btn">❗ Report Error</button>
  </a>
</div>

</div>

<!-- Styling For Big, Unique Buttons -->
<style>
.nexus-button {
  font-size: 1.4rem;
  font-weight: bold;
  padding: 1.2rem 2.4rem;
  margin: 0.5rem 0;
  border: none;
  border-radius: 2.5rem;
  background: linear-gradient(90deg, #0f2027, #2c5364, #00c6ff);
  color: #fff;
  box-shadow: 0 4px 16px rgba(44,83,100,.18);
  cursor: pointer;
  transition: transform 0.11s, box-shadow 0.11s;
  outline: none;
  letter-spacing: 1px;
  min-width: 320px;
  max-width: 90vw;
  display: block;
  text-shadow: 0 2px 8px rgba(0,0,0,.07);
}
.nexus-button:hover {
  transform: scale(1.05);
  box-shadow: 0 6px 24px rgba(44,83,100,.22);
  background: linear-gradient(90deg, #00c6ff, #2c5364, #0f2027);
}
</style>

<!-- Auto-Typing Headings/Buttons (Live Words) -->
<script>
const typingData = [
  { id: "auto-type-title", words: ["NEXUS AI BOT", "AI WhatsApp Assistant", "Open Source AI Chatbot", "Deploy Instantly", "Connect. Pair. Chat."] },
  { id: "fork-btn", words: ["🍴 Fork this Repo", "🍴 Fork to Your Account!"] },
  { id: "session-btn", words: ["🔑 Get Session", "🔑 Get Free Pairing"] },
  { id: "github-follow-btn", words: ["⭐ Follow Me on GitHub", "⭐ Star & Follow!"] },
  { id: "whatsapp-btn", words: ["💬 Follow WhatsApp Channel", "💬 Join Updates!"] },
  { id: "heroku-btn", words: ["🚀 Deploy on Heroku", "🚀 1-Click Heroku Deploy"] },
  { id: "render-btn", words: ["🌐 Deploy on Render", "🌐 Fast Render Deploy"] },
  { id: "railway-btn", words: ["⚡ Deploy on Railway", "⚡ Easy Railway Deploy"] },
  { id: "report-btn", words: ["❗ Report Error", "❗ Found a Bug?"] },
];

// Typing Animation Utility
function autoType(element, words, idx = 0, char = 0, del = false) {
  if(!element) return;
  let currentWord = words[idx];
  if (!del) {
    element.innerText = currentWord.slice(0, char + 1);
    if (char < currentWord.length - 1) {
      setTimeout(() => autoType(element, words, idx, char + 1, false), 55);
    } else {
      setTimeout(() => autoType(element, words, idx, char, true), 1200);
    }
  } else {
    element.innerText = currentWord.slice(0, char - 1);
    if (char > 1) {
      setTimeout(() => autoType(element, words, idx, char - 1, true), 32);
    } else {
      setTimeout(() => autoType(element, words, (idx + 1) % words.length, 0, false), 380);
    }
  }
}

window.addEventListener('DOMContentLoaded', () => {
  typingData.forEach(({id, words}) => {
    const el = document.getElementById(id);
    if (el && words.length) autoType(el, words);
  });
});
</script>

<!-- 
  ⭐️ Thank you for checking out NEXUS AI BOT!
  Get started by clicking any big button above 🚀
-->
