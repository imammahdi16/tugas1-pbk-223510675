<template>
  <div class="resume-container">
    <header class="resume-header">
      <h1>MHD HAMMAM ALMAHDI</h1>
      <p>Software Engineer | mahdi@email.com | 08123456789</p>
    </header>

    <section class="work-experience">
      <h2>Pengalaman Kerja</h2>
      <div class="job">
        <h3>Senior Software Engineer</h3>
        <p>ABC Solutions | Juni 2018 - Sekarang</p>
        <ul>
          <li>
            Memimpin tim pengembang dalam implementasi aplikasi web yang
            skalabel.
          </li>
          <li>
            Bekerjasama dengan tim lintas fungsi untuk menghasilkan produk
            perangkat lunak berkualitas tinggi.
          </li>
        </ul>
      </div>
      <!-- Tambahkan pengalaman kerja lainnya di sini -->
    </section>

    <section class="education">
      <h2>Pendidikan</h2>
      <div class="school">
        <h3>Bachelor of Science dalam Ilmu Komputer</h3>
        <p>Universitas Islam Riau | 2022 - 2025</p>
      </div>
      <!-- Tambahkan pendidikan lainnya di sini -->
    </section>

    <section class="skills">
      <h2>Keterampilan</h2>
      <ul>
        <li>Mahir dalam JavaScript (ES6+), HTML5, CSS3</li>
        <li>Pengalaman dengan kerangka kerja Vue.js, React, dan Angular</li>
        <li>Familiar dengan kontrol versi Git dan metodologi Agile</li>
        <li>Kemampuan pemecahan masalah dan komunikasi yang kuat</li>
      </ul>
    </section>

    <section class="languages">
      <h2>Bahasa</h2>
      <ul>
        <li>Inggris (Lancar)</li>
        <li>Spanyol (Menengah)</li>
        <li>Prancis (Dasar)</li>
      </ul>
    </section>
  </div>
</template>

<script setup>
// Anda dapat menambahkan script yang diperlukan di sini
</script>

<style scoped>
.resume-container {
  max-width: 800px;
  margin: auto;
  padding: 20px;
  border: 1px solid #ccc;
  border-radius: 10px;
}

.resume-header {
  text-align: center;
  margin-bottom: 40px;
}

.work-experience,
.education,
.skills,
.languages {
  margin-bottom: 20px;
}

h2 {
  border-bottom: 2px solid #ccc;
  padding-bottom: 5px;
}

ul {
  list-style: none;
  padding: 0;
}

li {
  margin-bottom: 10px;
}
</style>
