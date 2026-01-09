<!-- Animated Background -->
<div align="center">
  <div class="morph-container">
    <!-- Animated shapes in background -->
    <div class="shape shape-1"></div>
    <div class="shape shape-2"></div>
    <div class="shape shape-3"></div>
    <div class="shape shape-4"></div>
    
    <!-- Main Content Container -->
    <div class="profile-card">
    
# 👋 Hello, I'm Mohamed Aboalhassan

<div class="location">
  <img src="https://cdn-icons-png.flaticon.com/512/197/197604.png" width="20" alt="Egypt Flag"/> 
  <span class="typing-text">Backend Developer from Cairo, Egypt</span>
</div>

<div class="tagline">Crafting robust backend solutions with Laravel & PHP</div>

---

## 🧠 **About Me**

<div class="about-card">
  <p>I'm a passionate **Backend Developer** specializing in **Laravel, PHP, and MySQL**. I focus on building scalable APIs, optimizing databases, and writing clean, maintainable code.</p>
  <p>Passionate about backend architecture, performance tuning, and delivering reliable systems that power amazing user experiences.</p>
</div>

---

## 🛠 **Tech Stack**

<div class="tech-stack">
  <div class="tech-item morph">
    <img src="https://img.icons8.com/color/48/000000/php.png" alt="PHP"/>
    <span>PHP</span>
  </div>
  <div class="tech-item morph">
    <img src="https://img.icons8.com/fluency/48/000000/laravel.png" alt="Laravel"/>
    <span>Laravel</span>
  </div>
  <div class="tech-item morph">
    <img src="https://img.icons8.com/color/48/000000/mysql-logo.png" alt="MySQL"/>
    <span>MySQL</span>
  </div>
  <div class="tech-item morph">
    <img src="https://img.icons8.com/color/48/000000/git.png" alt="Git"/>
    <span>Git</span>
  </div>
  <div class="tech-item morph">
    <img src="https://img.icons8.com/color/48/000000/api.png" alt="API"/>
    <span>REST API</span>
  </div>
</div>

<div class="skills-badges">
  <span class="badge morph">OOP</span>
  <span class="badge morph">Database Design</span>
  <span class="badge morph">System Architecture</span>
  <span class="badge morph">Performance Tuning</span>
  <span class="badge morph">Clean Code</span>
</div>

---

## 🚀 **Featured Projects**

<div class="projects-grid">
  
  <div class="project-card morph">
    <h3>☀️ Solar Energy E-commerce</h3>
    <p>Full-featured e-commerce platform backend for solar energy products</p>
    <div class="project-stats">
      <a href="https://github.com/memo4code2/Solar-ecommerce" class="project-link">
        <img src="https://img.shields.io/github/stars/memo4code2/Solar-ecommerce?style=flat-square&label=Stars&color=FFD700" alt="Stars"/>
        <img src="https://img.shields.io/github/forks/memo4code2/Solar-ecommerce?style=flat-square&label=Forks&color=blue" alt="Forks"/>
      </a>
    </div>
  </div>
  
  <div class="project-card morph">
    <h3>✅ Simple To-Do List</h3>
    <p>PHP/JS task management application</p>
    <div class="project-stats">
      <a href="https://github.com/memo4code2/Simple-To-Do-List" class="project-link">
        <img src="https://img.shields.io/github/stars/memo4code2/Simple-To-Do-List?style=flat-square&label=Stars&color=FFD700" alt="Stars"/>
        <img src="https://img.shields.io/github/forks/memo4code2/Simple-To-Do-List?style=flat-square&label=Forks&color=blue" alt="Forks"/>
      </a>
    </div>
  </div>
  
</div>

---

## 📊 **GitHub Stats**

<div class="stats-container">
  <div class="stat-item">
    <h4>🌱 Currently Learning</h4>
    <p>Advanced Laravel, System Design, Microservices</p>
  </div>
  <div class="stat-item">
    <h4>🎯 2024 Goals</h4>
    <p>Contribute to Open Source, Master Docker & DevOps</p>
  </div>
</div>

---

## 📫 **Let's Connect**

<div class="social-links">
  <a href="https://github.com/memo4code2" class="social-btn morph">
    <img src="https://img.icons8.com/fluency/30/000000/github.png" alt="GitHub"/>
    <span>GitHub</span>
  </a>
  <a href="mailto:memofastcup@gmail.com" class="social-btn morph">
    <img src="https://img.icons8.com/color/30/000000/gmail-new.png" alt="Gmail"/>
    <span>Email</span>
  </a>
  <a href="https://www.linkedin.com/in/mohamed-abolhassan-b16a803a0/" class="social-btn morph">
    <img src="https://img.icons8.com/color/30/000000/linkedin.png" alt="LinkedIn"/>
    <span>LinkedIn</span>
  </a>
</div>

---

<div class="footer">
  <p class="pulse-text">✨ Open to collaboration and new opportunities! ✨</p>
  <div class="visitor-counter">
    <img src="https://komarev.com/ghpvc/?username=memo4code2&color=blueviolet&style=flat-square" alt="Profile Views"/>
  </div>
</div>

    </div>
  </div>
</div>

<style>
/* Morph Animation Styles */
@keyframes morph {
  0%, 100% { border-radius: 60% 40% 30% 70% / 60% 30% 70% 40%; }
  50% { border-radius: 30% 60% 70% 40% / 50% 60% 30% 60%; }
}

@keyframes float {
  0%, 100% { transform: translateY(0px); }
  50% { transform: translateY(-10px); }
}

@keyframes pulse {
  0%, 100% { opacity: 1; }
  50% { opacity: 0.8; }
}

@keyframes typing {
  from { width: 0; }
  to { width: 100%; }
}

@keyframes gradient {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

.morph-container {
  position: relative;
  padding: 20px;
  max-width: 900px;
  margin: 0 auto;
}

.shape {
  position: absolute;
  background: linear-gradient(45deg, #6a11cb 0%, #2575fc 100%);
  opacity: 0.1;
  animation: morph 8s ease-in-out infinite, float 6s ease-in-out infinite;
  z-index: -1;
}

.shape-1 {
  width: 200px;
  height: 200px;
  top: 5%;
  left: 5%;
  animation-delay: 0s;
}

.shape-2 {
  width: 150px;
  height: 150px;
  top: 60%;
  right: 10%;
  background: linear-gradient(45deg, #ff9a9e 0%, #fad0c4 100%);
  animation-delay: -2s;
}

.shape-3 {
  width: 100px;
  height: 100px;
  bottom: 10%;
  left: 15%;
  background: linear-gradient(45deg, #a1c4fd 0%, #c2e9fb 100%);
  animation-delay: -4s;
}

.shape-4 {
  width: 120px;
  height: 120px;
  top: 20%;
  right: 20%;
  background: linear-gradient(45deg, #ffecd2 0%, #fcb69f 100%);
  animation-delay: -6s;
}

.profile-card {
  background: rgba(255, 255, 255, 0.95);
  backdrop-filter: blur(10px);
  border-radius: 20px;
  padding: 30px;
  box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1);
  border: 1px solid rgba(255, 255, 255, 0.2);
  animation: float 5s ease-in-out infinite;
}

.location {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 10px;
  margin: 15px 0;
  font-size: 1.1em;
  color: #555;
}

.typing-text {
  overflow: hidden;
  white-space: nowrap;
  animation: typing 3.5s steps(40, end);
  border-right: 2px solid;
}

.tagline {
  text-align: center;
  font-size: 1.2em;
  color: #666;
  margin-bottom: 30px;
  font-style: italic;
}

.about-card {
  background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%);
  padding: 20px;
  border-radius: 15px;
  margin: 20px 0;
  border-left: 5px solid #6a11cb;
}

.tech-stack {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
  margin: 30px 0;
}

.tech-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 15px;
  background: white;
  border-radius: 15px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;
  animation: float 3s ease-in-out infinite;
  animation-delay: calc(var(--i) * 0.2s);
}

.tech-item:hover {
  transform: translateY(-5px);
  box-shadow: 0 10px 25px rgba(0, 0, 0, 0.2);
}

.tech-item:nth-child(1) { --i: 1; animation-delay: 0.2s; }
.tech-item:nth-child(2) { --i: 2; animation-delay: 0.4s; }
.tech-item:nth-child(3) { --i: 3; animation-delay: 0.6s; }
.tech-item:nth-child(4) { --i: 4; animation-delay: 0.8s; }
.tech-item:nth-child(5) { --i: 5; animation-delay: 1s; }

.skills-badges {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 10px;
  margin: 20px 0;
}

.badge {
  padding: 8px 16px;
  background: linear-gradient(45deg, #6a11cb, #2575fc);
  color: white;
  border-radius: 25px;
  font-size: 0.9em;
  transition: all 0.3s ease;
}

.badge:hover {
  transform: scale(1.05);
  box-shadow: 0 5px 15px rgba(106, 17, 203, 0.3);
}

.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 20px;
  margin: 30px 0;
}

.project-card {
  background: white;
  padding: 20px;
  border-radius: 15px;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;
  border-top: 5px solid transparent;
  background: linear-gradient(white, white) padding-box,
              linear-gradient(45deg, #6a11cb, #2575fc) border-box;
  border: 5px solid transparent;
}

.project-card:hover {
  transform: translateY(-5px);
  box-shadow: 0 15px 30px rgba(0, 0, 0, 0.2);
}

.project-stats {
  margin-top: 15px;
  display: flex;
  gap: 10px;
}

.stats-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin: 30px 0;
}

.stat-item {
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  color: white;
  padding: 20px;
  border-radius: 15px;
  animation: pulse 2s ease-in-out infinite;
}

.social-links {
  display: flex;
  justify-content: center;
  gap: 20px;
  margin: 30px 0;
}

.social-btn {
  display: flex;
  align-items: center;
  gap: 10px;
  padding: 12px 24px;
  background: white;
  border-radius: 50px;
  text-decoration: none;
  color: #333;
  box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
  transition: all 0.3s ease;
}

.social-btn:hover {
  transform: translateY(-3px);
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.footer {
  margin-top: 40px;
  text-align: center;
}

.pulse-text {
  animation: pulse 2s infinite;
  font-size: 1.2em;
  color: #6a11cb;
  font-weight: bold;
}

.visitor-counter {
  margin-top: 20px;
}

@media (max-width: 768px) {
  .tech-stack {
    gap: 10px;
  }
  
  .tech-item {
    padding: 10px;
  }
  
  .social-links {
    flex-direction: column;
    align-items: center;
  }
}
</style>

<script>
// Simple script for interactive elements
document.addEventListener('DOMContentLoaded', function() {
  // Add hover effects to morph elements
  const morphElements = document.querySelectorAll('.morph');
  
  morphElements.forEach(el => {
    el.addEventListener('mouseenter', function() {
      this.style.animation = 'morph 2s ease-in-out, float 1s ease-in-out';
    });
    
    el.addEventListener('mouseleave', function() {
      this.style.animation = '';
    });
  });
  
  // Update visitor count (simulated - in reality you'd use GitHub API)
  const visitorCount = document.querySelector('.visitor-counter');
  if (visitorCount) {
    setTimeout(() => {
      visitorCount.innerHTML += '<p style="margin-top: 5px; font-size: 0.9em; color: #666;">Thanks for visiting! 🚀</p>';
    }, 2000);
  }
});
</script>
