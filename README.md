<style>
@keyframes slideInDown { from { opacity: 0; transform: translateY(-30px); } to { opacity: 1; transform: translateY(0); } }
@keyframes slideInUp { from { opacity: 0; transform: translateY(30px); } to { opacity: 1; transform: translateY(0); } }
@keyframes glow { 0%, 100% { box-shadow: 0 0 20px rgba(56, 189, 248, 0.3), 0 0 40px rgba(56, 189, 248, 0.1); } 50% { box-shadow: 0 0 40px rgba(56, 189, 248, 0.6), 0 0 80px rgba(56, 189, 248, 0.3), inset 0 0 20px rgba(56, 189, 248, 0.1); } }
@keyframes floatAnimation { 0%, 100% { transform: translateY(0px); } 50% { transform: translateY(-10px); } }
@keyframes pulse { 0%, 100% { opacity: 1; transform: scale(1); } 50% { opacity: 0.85; transform: scale(0.98); } }
@keyframes gradientShift { 0% { background-position: 0% 50%; } 50% { background-position: 100% 50%; } 100% { background-position: 0% 50%; } }
@keyframes typewriter { 0% { width: 0; } 100% { width: 100%; } }
@keyframes blink { 0%, 50%, 100% { opacity: 1; } 51%, 99% { opacity: 0; } }
@keyframes waveRipple { 0% { box-shadow: 0 0 0 0 rgba(56, 189, 248, 0.7); } 70% { box-shadow: 0 0 0 10px rgba(56, 189, 248, 0); } 100% { box-shadow: 0 0 0 0 rgba(56, 189, 248, 0); } }
@keyframes cardFlip { 0% { transform: rotateX(0); } 50% { transform: rotateX(10deg); } 100% { transform: rotateX(0); } }
@keyframes shimmer { 0% { background-position: -1000px 0; } 100% { background-position: 1000px 0; } }
@keyframes rainbow { 0% { filter: hue-rotate(0deg); } 100% { filter: hue-rotate(360deg); } }
@keyframes bounce { 0%, 100% { transform: translateY(0); } 50% { transform: translateY(-20px); } }
@keyframes rotateSpin { 0% { transform: rotate(0deg); } 100% { transform: rotate(360deg); } }
.premium-header { animation: slideInDown 0.8s ease-out, glow 3s ease-in-out infinite; border-radius: 16px !important; backdrop-filter: blur(10px); transition: all 0.3s ease; }
.premium-header:hover { transform: translateY(-5px); box-shadow: 0 0 60px rgba(56, 189, 248, 0.5), inset 0 1px 0 rgba(255, 255, 255, 0.2); animation: waveRipple 0.6s; }
.premium-title { background: linear-gradient(90deg, #38bdf8, #0369a1, #06b6d4, #38bdf8); background-size: 300% 300%; -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; font-weight: 900; letter-spacing: 2px; animation: slideInDown 1s ease-out 0.2s both, gradientShift 6s ease infinite, rainbow 8s linear infinite; text-shadow: 0 0 30px rgba(56, 189, 248, 0.3); }
.premium-subtitle { animation: slideInDown 1.2s ease-out 0.4s both, bounce 3s ease-in-out 1.2s infinite; color: #94a3b8; font-style: italic; letter-spacing: 1px; }
.badge-premium { display: inline-block; border-radius: 8px; overflow: hidden; transition: all 0.3s ease; }
.badge-premium:hover { transform: translateY(-4px) scale(1.05); filter: brightness(1.2); }
.card-container { perspective: 1000px; }
.card-flip { animation: cardFlip 2s ease-in-out infinite; transform-style: preserve-3d; }
@media (max-width: 768px) {
  .stats-container { flex-direction: column !important; }
  .stat-item { width: 100%; margin: 10px 0; }
  .premium-title { font-size: 1.5em; letter-spacing: 1px; }
  .badge-premium { width: 90%; }
}
</style>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=rect&height=220&color=0f172a&text=Rabbi%20Hossain&fontSize=80&fontColor=38bdf8&animation=fadeIn&fontAlignY=50" width="100%" alt="Header Dashboard" class="premium-header" style="border-radius: 16px; box-shadow: 0 0 40px rgba(56, 189, 248, 0.3), inset 0 1px 0 rgba(255, 255, 255, 0.1);"/>

# 🖥️ <span class="premium-title">Full-Stack Web Developer</span>
> <span class="premium-subtitle">Transforming complex problems into minimalist digital solutions.</span>

---

## 📊 Developer Status Dashboard

<table style="width: 100%;">
  <tr>
    <td align="center" width="33%" style="padding: 15px;">
      <img src="https://img.shields.io/badge/Expertise-Frontend-38bdf8?style=for-the-badge&logo=react" alt="Frontend Expertise" class="badge-premium" style="animation: slideInUp 1s ease-out 0.2s both, floatAnimation 3s ease-in-out infinite;"/><br/>
      <sub style="animation: slideInUp 1.2s ease-out 0.3s both; display: inline-block; color: #38bdf8; font-weight: 600; margin-top: 10px;">React • Next.js • Tailwind</sub>
    </td>
    <td align="center" width="33%" style="padding: 15px;">
      <img src="https://img.shields.io/badge/Logic-Backend-0369a1?style=for-the-badge&logo=node.js" alt="Backend Logic" class="badge-premium" style="animation: slideInUp 1.05s ease-out 0.35s both, floatAnimation 3s ease-in-out 0.5s infinite;"/><br/>
      <sub style="animation: slideInUp 1.25s ease-out 0.45s both; display: inline-block; color: #0369a1; font-weight: 600; margin-top: 10px;">Node.js • Express • Django</sub>
    </td>
    <td align="center" width="33%" style="padding: 15px;">
      <img src="https://img.shields.io/badge/Storage-Database-0f172a?style=for-the-badge&logo=postgresql" alt="Database Storage" class="badge-premium" style="animation: slideInUp 1.1s ease-out 0.5s both, floatAnimation 3s ease-in-out 1s infinite;"/><br/>
      <sub style="animation: slideInUp 1.3s ease-out 0.6s both; display: inline-block; color: #64748b; font-weight: 600; margin-top: 10px;">PostgreSQL • MongoDB • SQL</sub>
    </td>
  </tr>
</table>

---

## ⚙️ Developer Workflow
*My systematic approach to building production-ready web products.*

<p align="center">
  <img src="https://img.shields.io/badge/%E2%97%8B_Concept-0f172a?style=for-the-badge&logoColor=white" alt="Concept" class="badge-premium" style="animation: slideInUp 1s ease-out 0.2s both, floatAnimation 2.5s ease-in-out infinite;"/> 
  <span style="color: #38bdf8; font-weight: bold; animation: pulse 2s ease-in-out 0.3s infinite; display: inline-block; margin: 0 10px;">➜</span>
  <img src="https://img.shields.io/badge/%E2%97%8B_Development-38bdf8?style=for-the-badge&logoColor=white" alt="Development" class="badge-premium" style="animation: slideInUp 1.1s ease-out 0.4s both, floatAnimation 2.5s ease-in-out 0.3s infinite;"/> 
  <span style="color: #0369a1; font-weight: bold; animation: pulse 2s ease-in-out 0.5s infinite; display: inline-block; margin: 0 10px;">➜</span>
  <img src="https://img.shields.io/badge/%E2%97%8B_Deployment-0369a1?style=for-the-badge&logoColor=white" alt="Deployment" class="badge-premium" style="animation: slideInUp 1.2s ease-out 0.6s both, floatAnimation 2.5s ease-in-out 0.6s infinite;"/>
</p>

</div>

---


## 🛰️ Developer Skill Orbit
*A circular breakdown of my core technical DNA*

<div align="center" style="animation: slideInUp 1.3s ease-out 0.2s both;">
  <div style="display: grid; grid-template-columns: 1fr 1fr; gap: 20px; margin: 20px auto; max-width: 1000px; padding: 0 20px;">
    <div class="card-container card-flip" style="background: linear-gradient(135deg, rgba(56, 189, 248, 0.1), rgba(3, 105, 161, 0.1)); padding: 20px; border-radius: 16px; border: 2px solid rgba(56, 189, 248, 0.3); box-shadow: 0 8px 32px rgba(56, 189, 248, 0.1);">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=rabbihossainlhp&layout=donut&theme=tokyonight&hide_border=true&hide_title=true&langs_count=8" width="100%" style="max-width: 350px; filter: drop-shadow(0 0 15px rgba(56, 189, 248, 0.4)); border-radius: 12px; transition: all 0.3s ease; animation: slideInUp 1.4s ease-out 0.3s both;" alt="Tech Stack" onmouseover="this.style.filter='drop-shadow(0 0 25px rgba(56, 189, 248, 0.7))'; this.style.transform='scale(1.05)';" onmouseout="this.style.filter='drop-shadow(0 0 15px rgba(56, 189, 248, 0.4))'; this.style.transform='scale(1)';"/>
      <p style="color: #38bdf8; animation: slideInUp 1.5s ease-out 0.4s both; font-weight: 700; margin-top: 15px; letter-spacing: 1px;">💻 Tech Stack</p>
    </div>
    <div class="card-container card-flip" style="background: linear-gradient(135deg, rgba(3, 105, 161, 0.1), rgba(56, 189, 248, 0.1)); padding: 20px; border-radius: 16px; border: 2px solid rgba(3, 105, 161, 0.3); box-shadow: 0 8px 32px rgba(3, 105, 161, 0.1);">
       <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=rabbihossainlhp&theme=tokyonight" width="100%" style="max-width: 350px; filter: drop-shadow(0 0 15px rgba(3, 105, 161, 0.4)); border-radius: 12px; transition: all 0.3s ease; animation: slideInUp 1.45s ease-out 0.35s both;" alt="Contribution" onmouseover="this.style.filter='drop-shadow(0 0 25px rgba(3, 105, 161, 0.7))'; this.style.transform='scale(1.05)';" onmouseout="this.style.filter='drop-shadow(0 0 15px rgba(3, 105, 161, 0.4))'; this.style.transform='scale(1)';"/>
       <p style="color: #0369a1; animation: slideInUp 1.55s ease-out 0.45s both; font-weight: 700; margin-top: 15px; letter-spacing: 1px;">📊 Contributions</p>
    </div>
  </div>
</div>

---

## 🛠️ THE CORE STACK

<p align="center" style="display: flex; justify-content: center; flex-wrap: wrap; gap: 15px; padding: 20px;">
  <img src="https://img.shields.io/badge/-React-0f172a?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" class="badge-premium" style="animation: slideInUp 1.2s ease-out 0.1s both, bounce 2s ease-in-out 1.2s infinite; cursor: pointer;"/>
  <img src="https://img.shields.io/badge/-Next.js-0f172a?style=for-the-badge&logo=nextdotjs&logoColor=white" alt="Next.js" class="badge-premium" style="animation: slideInUp 1.25s ease-out 0.2s both, bounce 2s ease-in-out 1.4s infinite; cursor: pointer;"/>
  <img src="https://img.shields.io/badge/-TypeScript-0f172a?style=for-the-badge&logo=typescript&logoColor=3178C6" alt="TypeScript" class="badge-premium" style="animation: slideInUp 1.3s ease-out 0.3s both, bounce 2s ease-in-out 1.6s infinite; cursor: pointer;"/>
  <img src="https://img.shields.io/badge/-Node.js-0f172a?style=for-the-badge&logo=nodedotjs&logoColor=339933" alt="Node.js" class="badge-premium" style="animation: slideInUp 1.35s ease-out 0.4s both, bounce 2s ease-in-out 1.8s infinite; cursor: pointer;"/>
  <img src="https://img.shields.io/badge/-PostgreSQL-0f172a?style=for-the-badge&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" class="badge-premium" style="animation: slideInUp 1.4s ease-out 0.5s both, bounce 2s ease-in-out 2s infinite; cursor: pointer;"/>
  <img src="https://img.shields.io/badge/-Tailwind-0f172a?style=for-the-badge&logo=tailwind-css&logoColor=06B6D4" alt="Tailwind CSS" class="badge-premium" style="animation: slideInUp 1.45s ease-out 0.6s both, bounce 2s ease-in-out 2.2s infinite; cursor: pointer;"/>
</p>

---

## 📊 VITAL DEVELOPER METRICS

<div align="center" style="backdrop-filter: blur(20px); padding: 25px 20px; border-radius: 16px; border: 2px solid rgba(56, 189, 248, 0.3); background: linear-gradient(135deg, rgba(56, 189, 248, 0.05), rgba(3, 105, 161, 0.05)); box-shadow: 0 8px 32px rgba(56, 189, 248, 0.1), inset 0 1px 0 rgba(255, 255, 255, 0.1); animation: slideInUp 1.4s ease-out 0.2s both; min-height: 500px;">
  <div class="stats-container" style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap; width: 100%;">
    <div class="stat-item card-flip" style="flex: 1; min-width: 280px; max-width: 48%; perspective: 1000px;">
      <img src="https://github-readme-stats.vercel.app/api?username=rabbihossainlhp&show_icons=true&theme=tokyonight&rank_icon=github&display_format=white&hide_border=true" width="100%" style="filter: drop-shadow(0 0 20px rgba(56, 189, 248, 0.5)); border-radius: 12px; transition: all 0.3s ease; animation: slideInUp 1.5s ease-out 0.3s both; cursor: pointer; box-shadow: 0 4px 20px rgba(56, 189, 248, 0.2);" alt="GitHub Stats" onmouseover="this.style.filter='drop-shadow(0 0 35px rgba(56, 189, 248, 0.9))'; this.style.transform='scale(1.05) translateY(-5px)';" onmouseout="this.style.filter='drop-shadow(0 0 20px rgba(56, 189, 248, 0.5))'; this.style.transform='scale(1) translateY(0)';"/>
    </div>
    <div class="stat-item card-flip" style="flex: 1; min-width: 280px; max-width: 48%; perspective: 1000px;">
      <img src="https://streak-stats.demolab.com?user=rabbihossainlhp&theme=tokyonight&hide_border=true" width="100%" style="filter: drop-shadow(0 0 20px rgba(56, 189, 248, 0.5)); border-radius: 12px; transition: all 0.3s ease; animation: slideInUp 1.55s ease-out 0.4s both; cursor: pointer; box-shadow: 0 4px 20px rgba(56, 189, 248, 0.2);" alt="Streak Stats" onmouseover="this.style.filter='drop-shadow(0 0 35px rgba(56, 189, 248, 0.9))'; this.style.transform='scale(1.05) translateY(-5px)';" onmouseout="this.style.filter='drop-shadow(0 0 20px rgba(56, 189, 248, 0.5))'; this.style.transform='scale(1) translateY(0)';"/>
    </div>
  </div>
</div>

<br />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=rabbihossainlhp&theme=tokyonight&hide_border=true&area=true" width="100%" style="filter: drop-shadow(0 0 20px rgba(3, 105, 161, 0.5)); border-radius: 12px; transition: all 0.3s ease; animation: slideInUp 1.5s ease-out 0.3s both, shimmer 3s ease-in-out infinite alternate; cursor: pointer; max-width: 100%; height: auto; display: block; margin: 20px auto;" alt="Activity Graph" onmouseover="this.style.filter='drop-shadow(0 0 35px rgba(3, 105, 161, 0.9))'; this.style.transform='scale(1.02) translateY(-5px)';" onmouseout="this.style.filter='drop-shadow(0 0 20px rgba(3, 105, 161, 0.5))'; this.style.transform='scale(1) translateY(0)';"/>

---

## 🌐 CONNECT & COLLABORATE

<p align="center" style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
<a href="https://linkedin.com/in/lhphossainrabbi"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" class="badge-premium" style="animation: slideInUp 1.3s ease-out 0.2s both;"/></a>
<a href="https://x.com/rabbihossain06"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X (Twitter)" class="badge-premium" style="animation: slideInUp 1.35s ease-out 0.3s both;"/></a>
<a href="mailto:rabbihossainlhp@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" class="badge-premium" style="animation: slideInUp 1.4s ease-out 0.4s both;"/></a>
</p>

<br />

<div align="center" style="animation: slideInUp 1.5s ease-out 0.3s both; margin-top: 40px;">
  <sub style="background: linear-gradient(90deg, #38bdf8, #06b6d4, #0369a1, #38bdf8); background-size: 400% 400%; -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; font-weight: 700; font-size: 1.15em; animation: gradientShift 5s ease infinite, slideInDown 1s ease-out 0.2s both; letter-spacing: 1.5px; display: block; padding: 20px;"><b>✨ "Turning complex code into elegant user experiences." ✨</b></sub>
  <br />
  <img src="https://capsule-render.vercel.app/api?type=rect&height=50&color=38bdf8&opacity=0.2&animation=fadeIn" width="100%" style="border-radius: 8px; box-shadow: 0 0 30px rgba(56, 189, 248, 0.4), inset 0 1px 0 rgba(255, 255, 255, 0.1); margin-top: 20px; animation: slideInUp 1.6s ease-out 0.4s both, bounce 3s ease-in-out 1.6s infinite;" alt="Footer"/>
</div>

</div>
