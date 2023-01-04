<script setup>
import Header from '../components/Header.vue'
import Banner from '../components/Banner.vue'
import Sidebar from '../components/Sidebar.vue'
</script>

<template>
  <Header/>
  <Banner/>
  <main class="flex">
    <Sidebar/>
    <div class="flex-1 p-10">


      <p class="text-3xl font-semibold">Visi & Misi Desa Kabasiran</p>
      <p class="text-3xl font-semibold">Visi</p>
      <p>Terwujudnya masyarakat yang maju, mandiri, sejahtera, berlandaskan iman dan taqwa </p><br>

      <p class="text-3xl font-semibold">Misi</p>
      <p> Menegakkan supermasi hukum</p>
      <p> Mewujudkan pemerintahan yang baik (good govermen)</P>
      <p> Meningkatkan peran serta masyarakat dalam pembangunan daerah</p>
      <p> Memelihara ketentraman dan ketertiban masyarakat</p>
      <p> Meningkatkan taraf kesejahteraan rakyat</p>
      <p> Meningkatkan perekonomian daerah</p>
      <p> Memantapkan kualitas iman dan taqwa</p>
      <p class="text-3xl font-semibold my-4">Struktur Desa</p>
      <img src="@/assets/struktur-desa.png" alt=""/>
    </div>
  </main>
</template>

<style>
  body{
    background: #f1f1f1;
  }
</style>
