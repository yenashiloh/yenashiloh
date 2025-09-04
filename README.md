<svg width="1200" height="400" xmlns="http://www.w3.org/2000/svg">
  <!-- Background Gradient -->
  <defs>
    <linearGradient id="bgGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0f172a;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#1e293b;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#334155;stop-opacity:1" />
    </linearGradient>
    
    <linearGradient id="textGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#22d3ee;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#a855f7;stop-opacity:1" />
    </linearGradient>
    
    <!-- Purple accent gradient for corner -->
    <radialGradient id="purpleAccent" cx="100%" cy="100%" r="50%">
      <stop offset="0%" style="stop-color:#a855f7;stop-opacity:0.3" />
      <stop offset="100%" style="stop-color:#a855f7;stop-opacity:0" />
    </radialGradient>
  </defs>
  
  <!-- Background -->
  <rect width="1200" height="400" fill="url(#bgGradient)"/>
  
  <!-- Purple accent corner -->
  <ellipse cx="1200" cy="400" rx="300" ry="200" fill="url(#purpleAccent)"/>
  
  <!-- Floating Icons -->
  
  <!-- HTML5 Icon -->
  <g transform="translate(80, 60)" opacity="0.4">
    <path d="M10 0L8 36h24l-2-36H10zm4 8h16l-1 16H15l-1-16z" fill="#22d3ee" stroke="#22d3ee" stroke-width="1"/>
    <rect x="14" y="12" width="12" height="2" fill="#22d3ee"/>
    <rect x="14" y="16" width="8" height="2" fill="#22d3ee"/>
  </g>
  
  <!-- CSS3 Icon -->
  <g transform="translate(180, 120)" opacity="0.3">
    <circle cx="15" cy="15" r="12" fill="none" stroke="#a855f7" stroke-width="2"/>
    <path d="M10 10h10v10h-10z" fill="#a855f7"/>
  </g>
  
  <!-- JavaScript Icon -->
  <g transform="translate(320, 40)" opacity="0.5">
    <rect x="5" y="5" width="20" height="20" rx="3" fill="#f59e0b"/>
    <text x="15" y="20" text-anchor="middle" font-family="Arial, sans-serif" font-size="12" fill="#0f172a">JS</text>
  </g>
  
  <!-- React Icon -->
  <g transform="translate(480, 100)" opacity="0.4">
    <circle cx="15" cy="15" r="3" fill="#22d3ee"/>
    <ellipse cx="15" cy="15" rx="12" ry="5" fill="none" stroke="#22d3ee" stroke-width="2"/>
    <ellipse cx="15" cy="15" rx="12" ry="5" fill="none" stroke="#22d3ee" stroke-width="2" transform="rotate(60 15 15)"/>
    <ellipse cx="15" cy="15" rx="12" ry="5" fill="none" stroke="#22d3ee" stroke-width="2" transform="rotate(120 15 15)"/>
  </g>
  
  <!-- Database Icon -->
  <g transform="translate(650, 70)" opacity="0.3">
    <ellipse cx="15" cy="8" rx="12" ry="4" fill="#10b981"/>
    <rect x="3" y="8" width="24" height="12" fill="#10b981"/>
    <ellipse cx="15" cy="20" rx="12" ry="4" fill="#10b981"/>
  </g>
  
  <!-- Design/Figma Icon -->
  <g transform="translate(800, 130)" opacity="0.4">
    <rect x="8" y="5" width="8" height="12" rx="4" fill="#a855f7"/>
    <rect x="16" y="5" width="8" height="8" rx="4" fill="#ef4444"/>
    <circle cx="12" cy="21" r="4" fill="#22d3ee"/>
  </g>
  
  <!-- Git Branch Icon -->
  <g transform="translate(950, 50)" opacity="0.3">
    <circle cx="5" cy="5" r="3" fill="#22d3ee"/>
    <circle cx="25" cy="25" r="3" fill="#22d3ee"/>
    <path d="M5 8 Q15 15 25 22" fill="none" stroke="#22d3ee" stroke-width="2"/>
  </g>
  
  <!-- Code Brackets -->
  <g transform="translate(1050, 90)" opacity="0.4">
    <path d="M5 10L0 15L5 20M15 10L20 15L15 20" fill="none" stroke="#10b981" stroke-width="2"/>
  </g>
  
  <!-- Responsive Design Icon -->
  <g transform="translate(120, 280)" opacity="0.3">
    <rect x="2" y="5" width="16" height="10" rx="1" fill="none" stroke="#a855f7" stroke-width="1.5"/>
    <rect x="20" y="8" width="8" height="6" rx="1" fill="none" stroke="#a855f7" stroke-width="1.5"/>
    <rect x="30" y="10" width="4" height="4" rx="0.5" fill="none" stroke="#a855f7" stroke-width="1"/>
  </g>
  
  <!-- API/Server Icon -->
  <g transform="translate(280, 320)" opacity="0.4">
    <rect x="5" y="5" width="20" height="4" rx="2" fill="#22d3ee"/>
    <rect x="5" y="11" width="20" height="4" rx="2" fill="#22d3ee"/>
    <rect x="5" y="17" width="20" height="4" rx="2" fill="#22d3ee"/>
  </g>
  
  <!-- UI/UX Wireframe Icon -->
  <g transform="translate(450, 300)" opacity="0.3">
    <rect x="2" y="2" width="26" height="20" rx="2" fill="none" stroke="#10b981" stroke-width="1.5"/>
    <rect x="5" y="5" width="8" height="3" fill="#10b981"/>
    <rect x="5" y="10" width="20" height="2" fill="#10b981"/>
    <rect x="5" y="14" width="15" height="2" fill="#10b981"/>
    <rect x="5" y="18" width="12" height="2" fill="#10b981"/>
  </g>
  
  <!-- Color Palette Icon -->
  <g transform="translate(620, 320)" opacity="0.4">
    <circle cx="8" cy="8" r="6" fill="#ef4444"/>
    <circle cx="16" cy="8" r="6" fill="#f59e0b"/>
    <circle cx="24" cy="8" r="6" fill="#10b981"/>
    <circle cx="12" cy="16" r="6" fill="#22d3ee"/>
    <circle cx="20" cy="16" r="6" fill="#a855f7"/>
  </g>
  
  <!-- Settings/Cog Icon -->
  <g transform="translate(780, 280)" opacity="0.3">
    <circle cx="15" cy="15" r="6" fill="none" stroke="#f59e0b" stroke-width="2"/>
    <circle cx="15" cy="15" r="3" fill="#f59e0b"/>
    <rect x="13" y="2" width="4" height="6" fill="#f59e0b"/>
    <rect x="13" y="22" width="4" height="6" fill="#f59e0b"/>
    <rect x="2" y="13" width="6" height="4" fill="#f59e0b"/>
    <rect x="22" y="13" width="6" height="4" fill="#f59e0b"/>
  </g>
  
  <!-- Component/Module Icon -->
  <g transform="translate(920, 300)" opacity="0.4">
    <rect x="2" y="2" width="12" height="12" rx="2" fill="none" stroke="#22d3ee" stroke-width="1.5"/>
    <rect x="16" y="2" width="12" height="12" rx="2" fill="none" stroke="#22d3ee" stroke-width="1.5"/>
    <rect x="2" y="16" width="12" height="12" rx="2" fill="none" stroke="#22d3ee" stroke-width="1.5"/>
    <rect x="16" y="16" width="12" height="12" rx="2" fill="none" stroke="#22d3ee" stroke-width="1.5"/>
  </g>
  
  <!-- Puzzle Piece Icon -->
  <g transform="translate(1080, 280)" opacity="0.3">
    <path d="M5 5h8v3c0 2 3 2 3 0v-3h8v8h-3c-2 0-2 3 0 3h3v8h-8v-3c0-2-3-2-3 0v3H5V13h3c2 0 2-3 0-3H5V5z" fill="#a855f7"/>
  </g>
  
  <!-- Main Text Content -->
  <g transform="translate(600, 200)">
    <text x="0" y="0" text-anchor="middle" font-family="Arial, sans-serif" font-size="48" font-weight="bold" fill="url(#textGradient)">
      WEB DEVELOPER
    </text>
    <text x="0" y="40" text-anchor="middle" font-family="Arial, sans-serif" font-size="48" font-weight="bold" fill="url(#textGradient)">
      &amp; UI/UX DESIGNER
    </text>
    <text x="0" y="70" text-anchor="middle" font-family="Arial, sans-serif" font-size="18" fill="#94a3b8" font-weight="300">
      TURNING IDEAS INTO INTERACTIVE EXPERIENCES
    </text>
  </g>
</svg>

# Hi there! 👋 I'm Shiloh Eugenio

> **Full-Stack Web Developer & UI/UX Designer** passionate about creating digital experiences that matter.

## 🚀 About Me

I'm a versatile developer who bridges the gap between beautiful design and functional code. With expertise spanning both frontend and backend technologies, I enjoy crafting complete web solutions from concept to deployment. When I'm not coding, you'll find me exploring the latest design trends or fine-tuning user experiences.

- 🔭 Currently working on exciting web projects
- 🌱 Always learning and staying updated with the latest tech trends
- 💡 Love turning creative ideas into reality through code
- 🎯 Goal: Building impactful applications that solve real-world problems

## 💻 Tech Stack

### **Frontend Development**
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### **Backend Development**
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)

### **Databases**
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

### **Tools & APIs**
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Trello](https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white)

### **Design & Creative**
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Adobe XD](https://img.shields.io/badge/Adobe_XD-470137?style=for-the-badge&logo=adobe-xd&logoColor=white)
![Adobe Photoshop](https://img.shields.io/badge/Adobe_Photoshop-31A8FF?style=for-the-badge&logo=adobe-photoshop&logoColor=white)
![Adobe Premiere Pro](https://img.shields.io/badge/Adobe_Premiere_Pro-9999FF?style=for-the-badge&logo=adobe-premiere-pro&logoColor=white)
![Sketch](https://img.shields.io/badge/Sketch-F7B500?style=for-the-badge&logo=sketch&logoColor=black)
![Canva](https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white)

## 📊 GitHub Stats

<div align="center">
  
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=yenashiloh&show_icons=true&theme=radical&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=yenashiloh&layout=compact&theme=radical&hide_border=true)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=yenashiloh&theme=radical&hide_border=true)

</div>

## 🏆 What I Bring to the Table

```javascript
const skills = {
    frontend: ["Responsive Design", "Interactive UIs", "Modern CSS"],
    backend: ["RESTful APIs", "Database Design", "MVC Architecture"],
    design: ["UI/UX Design", "Prototyping", "Brand Identity"],
    workflow: ["Agile Development", "Version Control", "Project Management"]
};
```

## 📫 Let's Connect!

I'm always excited to collaborate on interesting projects or discuss new opportunities!

[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://yenashiloh.github.io/shiloh-portfolio/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shiloh-eugenio-9a7024256/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:shiloheugenio21@gmail.com)
[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/shiloheugenio21)  

---

⭐️ From [Shiloh Eugenio](https://github.com/yenashiloh) | *"Turning ideas into interactive experiences"*
