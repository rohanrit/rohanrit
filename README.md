<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ritesh Rohan - Portfolio</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- FontAwesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" />
</head>
<body class="bg-[#191d29] text-gray-200 font-sans antialiased selection:bg-blue-500 selection:text-white">

  <!-- Header / Navbar -->
  <header class="max-w-6xl mx-auto px-6 py-6 flex justify-between items-center border-b border-gray-800">
    <div class="text-2xl font-bold tracking-wide">
      <span class="text-white">Dev</span><span class="text-blue-500">OK</span><span class="text-white">Dev</span>
    </div>
    <div>
      <button class="p-2 text-yellow-400 hover:text-yellow-300 transition">
        <i class="fa-solid fa-sun text-xl"></i>
      </button>
    </div>
  </header>

  <main class="max-w-6xl mx-auto px-6 py-12 space-y-20">

    <!-- Hero Section -->
    <section class="flex flex-col-reverse md:flex-row items-center justify-between gap-10">
      <div class="space-y-4 max-w-2xl">
        <h3 class="text-lg font-medium text-gray-300">Hi there, It's Me</h3>
        <h1 class="text-4xl md:text-5xl font-extrabold text-blue-500">Ritesh Rohan</h1>
        
        <p class="text-xs font-semibold text-gray-400 tracking-wide uppercase">
          Currently working as UI Developer | Frontend Developer | Full Stack Web Developer | Content Creator | Tech Enthusiast
        </p>

        <p class="text-sm text-gray-400 leading-relaxed">
          I'm a Frontend Developer specializing in React.js, Next.js, and modern Web Technologies. Focused on building responsive, high-performance web applications with exceptional UI/UX design.
        </p>

        <!-- Social Icons -->
        <div class="flex items-center gap-3 pt-2">
          <a href="#" class="w-9 h-9 rounded-full border border-gray-700 flex items-center justify-center text-gray-300 hover:border-blue-500 hover:text-blue-500 transition"><i class="fa-brands fa-github"></i></a>
          <a href="#" class="w-9 h-9 rounded-full border border-gray-700 flex items-center justify-center text-gray-300 hover:border-blue-500 hover:text-blue-500 transition"><i class="fa-brands fa-linkedin-in"></i></a>
          <a href="#" class="w-9 h-9 rounded-full border border-gray-700 flex items-center justify-center text-gray-300 hover:border-blue-500 hover:text-blue-500 transition"><i class="fa-brands fa-youtube"></i></a>
          <a href="#" class="w-9 h-9 rounded-full border border-gray-700 flex items-center justify-center text-gray-300 hover:border-blue-500 hover:text-blue-500 transition"><i class="fa-brands fa-instagram"></i></a>
          <a href="#" class="w-9 h-9 rounded-full border border-gray-700 flex items-center justify-center text-gray-300 hover:border-blue-500 hover:text-blue-500 transition"><i class="fa-solid fa-globe"></i></a>
        </div>
      </div>

      <!-- Profile Avatar -->
      <div class="relative">
        <div class="w-56 h-56 md:w-64 md:h-64 rounded-full overflow-hidden border-4 border-blue-500/80 shadow-2xl">
          <img src="YOUR_PROFILE_IMAGE.jpg" alt="Ritesh Rohan" class="w-full h-full object-cover" />
        </div>
      </div>
    </section>

    <!-- Skills & About Section -->
    <section class="grid grid-cols-1 md:grid-cols-2 gap-12 items-start">
      
      <!-- Core Skills -->
      <div class="space-y-6">
        <h2 class="text-2xl font-bold">Core <span class="text-blue-500">Skills</span></h2>
        
        <div class="space-y-4">
          <!-- HTML -->
          <div>
            <div class="flex justify-between text-xs font-semibold mb-1">
              <span>HTML</span>
              <span>90%</span>
            </div>
            <div class="w-full bg-gray-800 rounded-full h-2">
              <div class="bg-gray-300 h-2 rounded-full" style="width: 90%"></div>
            </div>
          </div>

          <!-- CSS -->
          <div>
            <div class="flex justify-between text-xs font-semibold mb-1">
              <span>CSS</span>
              <span>85%</span>
            </div>
            <div class="w-full bg-gray-800 rounded-full h-2">
              <div class="bg-gray-300 h-2 rounded-full" style="width: 85%"></div>
            </div>
          </div>

          <!-- JAVASCRIPT -->
          <div>
            <div class="flex justify-between text-xs font-semibold mb-1">
              <span>JAVASCRIPT</span>
              <span>80%</span>
            </div>
            <div class="w-full bg-gray-800 rounded-full h-2">
              <div class="bg-gray-300 h-2 rounded-full" style="width: 80%"></div>
            </div>
          </div>

          <!-- REACT.JS -->
          <div>
            <div class="flex justify-between text-xs font-semibold mb-1">
              <span>REACT.JS</span>
              <span>75%</span>
            </div>
            <div class="w-full bg-gray-800 rounded-full h-2">
              <div class="bg-gradient-to-r from-purple-500 to-indigo-500 h-2 rounded-full" style="width: 75%"></div>
            </div>
          </div>

          <!-- TAILWIND CSS -->
          <div>
            <div class="flex justify-between text-xs font-semibold mb-1">
              <span>TAILWIND CSS</span>
              <span>85%</span>
            </div>
            <div class="w-full bg-gray-800 rounded-full h-2">
              <div class="bg-gradient-to-r from-purple-500 to-indigo-500 h-2 rounded-full" style="width: 85%"></div>
            </div>
          </div>

          <!-- NODE.JS / EXPRESS -->
          <div>
            <div class="flex justify-between text-xs font-semibold mb-1">
              <span>NODE.JS</span>
              <span>70%</span>
            </div>
            <div class="w-full bg-gray-800 rounded-full h-2">
              <div class="bg-gradient-to-r from-purple-500 to-indigo-500 h-2 rounded-full" style="width: 70%"></div>
            </div>
          </div>
        </div>
      </div>

      <!-- About Me -->
      <div class="space-y-4">
        <h2 class="text-2xl font-bold">About <span class="text-blue-500">Me</span></h2>
        <p class="text-sm text-gray-400 leading-relaxed">
          I am Senior Frontend developer with 10+ years in IT/ITeS, 08 years in Figma/prototyping, and 10 years in graphic/web design—working at HCL, TechM, worked at Knorr, Scientific, TVS, Vedantu, EMFS—specializing in frontend maintenance and libraries for React/Next.js and conversion-focused UI.
        </p>
        <p class="text-sm text-gray-400 leading-relaxed">
          Having expertise knowledge in online website builders like WIX, SHOPIFY, Duda & Elementor/Wordpress. Recently built a Next.js PDF reading RAG extractor and custom Spotify/Audio API for horse data with TypeScript/Tailwind. Skills include React, Next.js, Node.js, Express, MongoDB, MySQL, Figma, and Adobe tools. Designer & photographer, best in image editing and restoration.
        </p>
      </div>
    </section>

    <!-- My Projects Section -->
    <section class="space-y-8 text-center">
      <h2 class="text-2xl font-bold">My <span class="text-blue-500">Projects</span></h2>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
        <!-- Project 1 -->
        <div class="bg-gray-800/50 rounded-xl overflow-hidden border border-gray-700/50 hover:border-blue-500 transition group">
          <div class="h-44 overflow-hidden bg-gray-900">
            <img src="YOUR_PROJECT_IMAGE_1.png" alt="Project 1" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
          </div>
          <div class="p-4 bg-[#1e2333]">
            <h4 class="text-sm font-semibold">Teq-Off-Next</h4>
          </div>
        </div>

        <!-- Project 2 -->
        <div class="bg-gray-800/50 rounded-xl overflow-hidden border border-gray-700/50 hover:border-blue-500 transition group">
          <div class="h-44 overflow-hidden bg-gray-900">
            <img src="YOUR_PROJECT_IMAGE_2.png" alt="Project 2" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
          </div>
          <div class="p-4 bg-[#1e2333]">
            <h4 class="text-sm font-semibold">Tevio UI</h4>
          </div>
        </div>

        <!-- Project 3 -->
        <div class="bg-gray-800/50 rounded-xl overflow-hidden border border-gray-700/50 hover:border-blue-500 transition group">
          <div class="h-44 overflow-hidden bg-gray-900">
            <img src="YOUR_PROJECT_IMAGE_3.png" alt="Project 3" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
          </div>
          <div class="p-4 bg-[#1e2333]">
            <h4 class="text-sm font-semibold">E-commerce Portal</h4>
          </div>
        </div>

        <!-- Project 4 -->
        <div class="bg-gray-800/50 rounded-xl overflow-hidden border border-gray-700/50 hover:border-blue-500 transition group">
          <div class="h-44 overflow-hidden bg-gray-900">
            <img src="YOUR_PROJECT_IMAGE_4.png" alt="Project 4" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
          </div>
          <div class="p-4 bg-[#1e2333]">
            <h4 class="text-sm font-semibold">EdTech Platform</h4>
          </div>
        </div>

        <!-- Project 5 -->
        <div class="bg-gray-800/50 rounded-xl overflow-hidden border border-gray-700/50 hover:border-blue-500 transition group">
          <div class="h-44 overflow-hidden bg-gray-900">
            <img src="YOUR_PROJECT_IMAGE_5.png" alt="Project 5" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
          </div>
          <div class="p-4 bg-[#1e2333]">
            <h4 class="text-sm font-semibold">Web App Dashboard</h4>
          </div>
        </div>

        <!-- Project 6 -->
        <div class="bg-gray-800/50 rounded-xl overflow-hidden border border-gray-700/50 hover:border-blue-500 transition group">
          <div class="h-44 overflow-hidden bg-gray-900">
            <img src="YOUR_PROJECT_IMAGE_6.png" alt="Project 6" class="w-full h-full object-cover group-hover:scale-105 transition duration-300" />
          </div>
          <div class="p-4 bg-[#1e2333]">
            <h4 class="text-sm font-semibold">SaaS Landing Page</h4>
          </div>
        </div>
      </div>

      <button class="px-6 py-2 bg-black text-white text-xs font-semibold rounded hover:bg-gray-900 border border-gray-700 transition">
        View More
      </button>
    </section>

    <!-- My Expertise Section -->
    <section class="space-y-8 text-center">
      <h2 class="text-2xl font-bold">My <span class="text-blue-500">Expertise</span></h2>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <!-- Card 1 -->
        <div class="bg-[#242b3d] p-6 rounded-xl space-y-3 text-center border border-gray-700/30">
          <div class="text-blue-400 text-3xl"><i class="fa-solid fa-code"></i></div>
          <h3 class="text-base font-semibold">Frontend Developer</h3>
          <p class="text-xs text-gray-400 leading-relaxed">
            Building responsive, component-driven Web Applications using React, Next.js, and modern CSS.
          </p>
        </div>

        <!-- Card 2 -->
        <div class="bg-[#242b3d] p-6 rounded-xl space-y-3 text-center border border-gray-700/30">
          <div class="text-blue-400 text-3xl"><i class="fa-solid fa-compass-drafting"></i></div>
          <h3 class="text-base font-semibold">UI/UX Developer</h3>
          <p class="text-xs text-gray-400 leading-relaxed">
            Focus on Prototyping, Wireframing, User Centric Interactive Design, and Modern Styling.
          </p>
        </div>

        <!-- Card 3 -->
        <div class="bg-[#242b3d] p-6 rounded-xl space-y-3 text-center border border-gray-700/30">
          <div class="text-blue-400 text-3xl"><i class="fa-solid fa-palette"></i></div>
          <h3 class="text-base font-semibold">Web & Graphic Designer</h3>
          <p class="text-xs text-gray-400 leading-relaxed">
            Creative Layouts, Branding, Banner/Poster Design & Vector Art Illustration.
          </p>
        </div>

        <!-- Card 4 -->
        <div class="bg-[#242b3d] p-6 rounded-xl space-y-3 text-center border border-gray-700/30">
          <div class="text-blue-400 text-3xl"><i class="fa-solid fa-image"></i></div>
          <h3 class="text-base font-semibold">Digital Artist, Photo Editor</h3>
          <p class="text-xs text-gray-400 leading-relaxed">
            Master in Photo Manipulation, Retouching, Restorations, and Image Editing.
          </p>
        </div>
      </div>
    </section>

    <!-- Get In Touch Section -->
    <section class="space-y-6">
      <h2 class="text-2xl font-bold">Get In <span class="text-blue-500">Touch</span></h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
        <!-- Contact Info -->
        <div class="space-y-4 text-sm text-gray-300">
          <div class="flex items-center gap-3">
            <i class="fa-solid fa-location-dot text-blue-500"></i>
            <span>Gurgaon, Haryana</span>
          </div>
          <div class="flex items-center gap-3">
            <i class="fa-solid fa-envelope text-blue-500"></i>
            <span>riteshrohan@gmail.com</span>
          </div>
          <div class="flex items-center gap-3">
            <i class="fa-brands fa-github text-blue-500"></i>
            <span>github.com/riteshrohan</span>
          </div>
        </div>

        <!-- Map Placeholder -->
        <div class="w-full h-56 rounded-xl overflow-hidden border border-gray-700 bg-gray-800">
          <iframe 
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d14030.089856950285!2d77.0266383!3d28.4594965!2m3!1f0!2f0!3f0!2m1!1i1024!2i768!4f13.1!3m3!1m2!1s0x390d19d582e38859%3A0x2cf5fe8e5c64b1e!2sGurugram%2C%20Haryana!5e0!3m2!1sen!2sin!4v1680000000000" 
            width="100%" 
            height="100%" 
            style="border:0;" 
            allowfullscreen="" 
            loading="lazy">
          </iframe>
        </div>
      </div>
    </section>

  </main>

  <!-- Footer -->
  <footer class="bg-gray-100 text-gray-700 py-10 mt-20 border-t border-gray-200">
    <div class="max-w-6xl mx-auto px-6 grid grid-cols-1 md:grid-cols-3 gap-8 text-xs">
      
      <!-- Brand & Socials -->
      <div class="space-y-4">
        <div class="text-xl font-bold tracking-wide">
          <span class="text-gray-900">Dev</span><span class="text-blue-600">OK</span><span class="text-gray-900">Dev</span>
        </div>
        <div class="flex items-center gap-2">
          <a href="#" class="w-7 h-7 rounded-full bg-gray-200 flex items-center justify-center text-gray-600 hover:bg-blue-600 hover:text-white transition"><i class="fa-brands fa-github"></i></a>
          <a href="#" class="w-7 h-7 rounded-full bg-gray-200 flex items-center justify-center text-gray-600 hover:bg-blue-600 hover:text-white transition"><i class="fa-brands fa-linkedin-in"></i></a>
          <a href="#" class="w-7 h-7 rounded-full bg-gray-200 flex items-center justify-center text-gray-600 hover:bg-blue-600 hover:text-white transition"><i class="fa-brands fa-youtube"></i></a>
          <a href="#" class="w-7 h-7 rounded-full bg-gray-200 flex items-center justify-center text-gray-600 hover:bg-blue-600 hover:text-white transition"><i class="fa-brands fa-instagram"></i></a>
          <a href="#" class="w-7 h-7 rounded-full bg-gray-200 flex items-center justify-center text-gray-600 hover:bg-blue-600 hover:text-white transition"><i class="fa-solid fa-globe"></i></a>
        </div>
      </div>

      <!-- About Links -->
      <div class="space-y-2">
        <h5 class="font-bold text-gray-900 uppercase">About Me</h5>
        <ul class="space-y-1 text-gray-500">
          <li><a href="#" class="hover:text-blue-600">Home</a></li>
          <li><a href="#" class="hover:text-blue-600">About</a></li>
          <li><a href="#" class="hover:text-blue-600">Services</a></li>
        </ul>
      </div>

      <!-- Quick Links -->
      <div class="space-y-2">
        <h5 class="font-bold text-gray-900 uppercase">Quick Links</h5>
        <ul class="space-y-1 text-gray-500">
          <li><a href="#" class="hover:text-blue-600">Portfolio</a></li>
          <li><a href="#" class="hover:text-blue-600">Projects</a></li>
        </ul>
      </div>

    </div>
  </footer>

</body>
</html>
