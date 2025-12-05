<!DOCTYPE html>
<html lang="en" class="dark">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio - Muhammad Farhan Octaviano</title>

  <!-- Tailwind -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- AOS Animation -->
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />

  <script>
    function toggleDarkMode() {
      document.documentElement.classList.toggle('dark');
    }
  </script>

  <style>
    body {
      background: linear-gradient(135deg, #0f172a, #1e293b, #334155);
      background-size: 400% 400%;
      animation: gradientShift 10s ease infinite;
    }
    @keyframes gradientShift {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .glass {
      background: rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(12px);
      border: 1px solid rgba(255, 255, 255, 0.2);
    }
  </style>

</head>

<body class="text-white">

  <!-- HERO SECTION -->
  <section class="text-center py-16 px-4" data-aos="fade-down">
    <img src="foto-farhan.jpg" alt="Foto Farhan"
         class="w-40 h-40 mx-auto rounded-full shadow-lg border-4 border-white/30 mb-6"
         data-aos="zoom-in" />

    <h1 class="text-4xl font-bold tracking-wide drop-shadow-lg">Muhammad Farhan Octaviano</h1>
    <p class="text-xl mt-2 text-blue-200">IT Support Specialist</p>

    <button onclick="toggleDarkMode()"
      class="mt-5 px-6 py-2 bg-white/20 hover:bg-white/40 text-white rounded-full transition backdrop-blur-md">
      Toggle Dark Mode
    </button>
  </section>


  <!-- CONTENT WRAPPER -->
  <main class="max-w-4xl mx-auto px-5">

    <!-- Profil -->
    <div class="glass rounded-xl p-6 mb-8 shadow-xl" data-aos="fade-up">
      <h2 class="text-2xl font-semibold mb-3 text-yellow-300">Profil Singkat</h2>
      <p class="text-gray-200 leading-relaxed">
        Saya adalah seorang IT Support berpengalaman di bidang Hardware Troubleshooting dalam lingkungan retail.
        Terampil menangani perangkat keras, software, jaringan, serta memiliki respon cepat & pemikiran kritis.
      </p>
    </div>

    <!-- Skills -->
    <div class="glass rounded-xl p-6 mb-8 shadow-xl" data-aos="fade-up" data-aos-delay="100">
      <h2 class="text-2xl font-semibold mb-3 text-yellow-300">Keahlian Utama</h2>
      <ul class="list-disc pl-6 text-gray-200 space-y-1">
        <li>Hardware Troubleshooting (PC, POS, Printer, Scanner)</li>
        <li>Software Troubleshooting</li>
        <li>Instalasi & Maintenance Perangkat</li>
        <li>Basic Networking (LAN, Wi-Fi, TCP/IP)</li>
        <li>Operating System (Windows & Linux dasar)</li>
        <li>Remote Support</li>
        <li>Technical Documentation</li>
      </ul>
    </div>

    <!-- Experience -->
    <div class="glass rounded-xl p-6 mb-8 shadow-xl" data-aos="fade-up" data-aos-delay="200">
      <h2 class="text-2xl font-semibold mb-3 text-yellow-300">Pengalaman Kerja</h2>

      <div class="mb-6">
        <h3 class="text-xl font-semibold text-blue-200">IT Support – PT. Indomarco Prismatama</h3>
        <p class="text-yellow-400 font-semibold">2021 – Sekarang</p>
        <ul class="list-disc pl-6 mt-2 text-gray-200 space-y-1">
          <li>Pemeliharaan perangkat IT retail</li>
          <li>Troubleshooting perangkat POS & jaringan</li>
          <li>Remote support</li>
        </ul>
      </div>

      <div class="mb-6">
        <h3 class="text-xl font-semibold text-blue-200">IT Support (Magang) – Kominfotik Kepulauan Seribu</h3>
        <p class="text-yellow-400 font-semibold">2018 – 2019</p>
        <ul class="list-disc pl-6 mt-2 text-gray-200 space-y-1">
          <li>Pemeliharaan komputer & jaringan</li>
          <li>Instalasi software & troubleshooting</li>
        </ul>
      </div>

      <div>
        <h3 class="text-xl font-semibold text-blue-200">Waitress – Kedai Tempe Mendoan & Tahu Slawi</h3>
        <p class="text-yellow-400 font-semibold">2016 – 2017</p>
        <ul class="list-disc pl-6 mt-2 text-gray-200 space-y-1">
          <li>Melayani pelanggan & operasional</li>
        </ul>
      </div>
    </div>

    <!-- Education -->
    <div class="glass rounded-xl p-6 mb-8 shadow-xl" data-aos="fade-up" data-aos-delay="300">
      <h2 class="text-2xl font-semibold mb-3 text-yellow-300">Pendidikan</h2>
      <p class="text-gray-200 font-semibold">Diploma III – Ilmu Komputer</p>
      <p class="text-gray-300">Universitas Bina Sarana Informatika (2017 – 2020)</p>
    </div>

    <!-- Certifications -->
    <div class="glass rounded-xl p-6 mb-8 shadow-xl" data-aos="fade-up" data-aos-delay="400">
      <h2 class="text-2xl font-semibold mb-3 text-yellow-300">Sertifikasi</h2>
      <ul class="list-disc pl-6 text-gray-200 space-y-1">
        <li>CCNA untuk Pemula</li>
        <li>LBPP LIA: Elementary – High Intermediate</li>
      </ul>
    </div>

    <!-- Contact -->
    <div class="glass rounded-xl p-6 mb-12 shadow-xl" data-aos="fade-up" data-aos-delay="500">
      <h2 class="text-2xl font-semibold mb-3 text-yellow-300">Kontak</h2>
      <p>Email: <span class="text-blue-300 font-semibold">farhan.octa16@gmail.com</span></p>
      <p>Telepon: 081219085203</p>
      <p>LinkedIn: 
        <a href="https://linkedin.com/in/farhan-octa-63904a112" class="text-blue-300 font-semibold hover:underline">
          linkedin.com/in/farhan-octa
        </a>
      </p>
    </div>

  </main>

  <!-- AOS Script -->
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>AOS.init();</script>

</body>
</html>
