<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Supachai Nilcha | Software Engineer & DevOps</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
  <style>
    body { font-family: 'Segoe UI', system-ui, sans-serif; }
    .hero-bg { background: linear-gradient(135deg, #1e3a8a 0%, #3b82f6 100%); }
    .skill-bar {
      height: 10px;
      background: #e5e7eb;
      border-radius: 9999px;
      overflow: hidden;
    }
    .skill-progress {
      height: 100%;
      background: linear-gradient(90deg, #3b82f6, #1e40af);
      border-radius: 9999px;
      transition: width 1.5s ease-in-out;
    }
  </style>
</head>
<body class="bg-gray-50 text-gray-800">

  <!-- Hero -->
  <section class="hero-bg text-white py-24">
    <div class="max-w-5xl mx-auto px-6 text-center">
      <h1 class="text-5xl font-bold mb-4">Supachai Nilcha</h1>
      <h2 class="text-2xl mb-6">Software Engineer | Full Stack Developer | DevOps Engineer</h2>
      <p class="text-xl max-w-2xl mx-auto mb-8">
        มากกว่า 10 ปี ประสบการณ์ในการพัฒนาซอฟต์แวร์และบริหารระบบไอที
      </p>
      <div class="flex justify-center gap-4">
        <a href="https://github.com/picthaisky" target="_blank" 
           class="bg-white text-blue-700 px-8 py-3 rounded-full font-semibold hover:bg-gray-100 transition">
          <i class="fab fa-github mr-2"></i> GitHub
        </a>
        <a href="mailto:picthaisky00@gmail.com" 
           class="bg-transparent border-2 border-white px-8 py-3 rounded-full font-semibold hover:bg-white hover:text-blue-700 transition">
          <i class="fas fa-envelope mr-2"></i> ติดต่อฉัน
        </a>
      </div>
    </div>
  </section>

  <!-- Skills with Graphics -->
  <section class="py-20 bg-white">
    <div class="max-w-5xl mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-4">Technical Skills</h2>
      <p class="text-center text-gray-600 mb-12">ระดับความเชี่ยวชาญ</p>
      
      <div class="grid md:grid-cols-2 gap-x-12 gap-y-10">
        
        <!-- Backend -->
        <div>
          <h3 class="font-semibold text-xl mb-6 flex items-center gap-3">
            <i class="fas fa-server text-blue-600"></i> Backend & Programming
          </h3>
          <div class="space-y-6">
            <div>
              <div class="flex justify-between mb-2">
                <span class="font-medium">C# .NET Core / ASP.NET Web API</span>
                <span class="text-blue-600 font-semibold">95%</span>
              </div>
              <div class="skill-bar"><div class="skill-progress w-[95%]"></div></div>
            </div>
            <div>
              <div class="flex justify-between mb-2">
                <span class="font-medium">Java Spring Boot</span>
                <span class="text-blue-600 font-semibold">85%</span>
              </div>
              <div class="skill-bar"><div class="skill-progress w-[85%]"></div></div>
            </div>
            <div>
              <div class="flex justify-between mb-2">
                <span class="font-medium">Python</span>
                <span class="text-blue-600 font-semibold">80%</span>
              </div>
              <div class="skill-bar"><div class="skill-progress w-[80%]"></div></div>
            </div>
          </div>
        </div>

        <!-- Frontend -->
        <div>
          <h3 class="font-semibold text-xl mb-6 flex items-center gap-3">
            <i class="fas fa-laptop-code text-blue-600"></i> Frontend
          </h3>
          <div class="space-y-6">
            <div>
              <div class="flex justify-between mb-2">
                <span class="font-medium">Angular + Material UI</span>
                <span class="text-blue-600 font-semibold">90%</span>
              </div>
              <div class="skill-bar"><div class="skill-progress w-[90%]"></div></div>
            </div>
            <div>
              <div class="flex justify-between mb-2">
                <span class="font-medium">React & JavaScript</span>
                <span class="text-blue-600 font-semibold">75%</span>
              </div>
              <div class="skill-bar"><div class="skill-progress w-[75%]"></div></div>
            </div>
          </div>
        </div>

        <!-- DevOps & Infrastructure -->
        <div>
          <h3 class="font-semibold text-xl mb-6 flex items-center gap-3">
            <i class="fas fa-cogs text-blue-600"></i> DevOps & Infrastructure
          </h3>
          <div class="space-y-6">
            <div>
              <div class="flex justify-between mb-2">
                <span class="font-medium">Windows / Linux Server Admin</span>
                <span class="text-blue-600 font-semibold">92%</span>
              </div>
              <div class="skill-bar"><div class="skill-progress w-[92%]"></div></div>
            </div>
            <div>
              <div class="flex justify-between mb-2">
                <span class="font-medium">Proxmox Virtualization</span>
                <span class="text-blue-600 font-semibold">88%</span>
              </div>
              <div class="skill-bar"><div class="skill-progress w-[88%]"></div></div>
            </div>
            <div>
              <div class="flex justify-between mb-2">
                <span class="font-medium">Docker, Git, Nginx, IIS</span>
                <span class="text-blue-600 font-semibold">85%</span>
              </div>
              <div class="skill-bar"><div class="skill-progress w-[85%]"></div></div>
            </div>
          </div>
        </div>

        <!-- Database -->
        <div>
          <h3 class="font-semibold text-xl mb-6 flex items-center gap-3">
            <i class="fas fa-database text-blue-600"></i> Database
          </h3>
          <div class="space-y-6">
            <div>
              <div class="flex justify-between mb-2">
                <span class="font-medium">MS SQL Server</span>
                <span class="text-blue-600 font-semibold">90%</span>
              </div>
              <div class="skill-bar"><div class="skill-progress w-[90%]"></div></div>
            </div>
            <div>
              <div class="flex justify-between mb-2">
                <span class="font-medium">MySQL / MongoDB</span>
                <span class="text-blue-600 font-semibold">80%</span>
              </div>
              <div class="skill-bar"><div class="skill-progress w-[80%]"></div></div>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- About, Experience, Projects, Contact (ย่อมาเพื่อความกระชับ) -->
  <!-- คุณสามารถนำส่วนอื่นๆ จากเวอร์ชันเก่าไปวางต่อได้ -->

  <section class="py-16 bg-gray-100">
    <div class="max-w-5xl mx-auto px-6 text-center">
      <h2 class="text-3xl font-bold mb-6">พร้อมพัฒนาโปรเจกต์คุณ</h2>
      <a href="mailto:picthaisky00@gmail.com" 
         class="bg-blue-600 text-white px-10 py-4 rounded-full text-lg font-semibold hover:bg-blue-700 inline-block">
        ส่งอีเมลหาฉัน
      </a>
    </div>
  </section>

  <footer class="bg-gray-900 text-white py-8 text-center">
    <p>© 2026 Supachai Nilcha. All Rights Reserved.</p>
  </footer>

</body>
</html>
