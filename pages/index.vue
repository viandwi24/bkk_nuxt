<template>
  <div>
    <!-- navbar -->
    <div class="container mx-auto px-12">
      <nav class="navbar home z-10">
        <div class="">
          <a href="#" class="navbar-header">BKK SMKN 1 MOJOKERTO</a>
        </div>
        <div class="navbar-menu">
          <a href="#" class="navbar-item">Papan Kerja</a>
          <a href="#" class="navbar-item">Magang</a>
          <a href="#" class="navbar-item">Tentang</a>
          <a href="#" class="navbar-item">Kontak</a>
          <nuxt-link to="/auth/register" tag="a" class="bg-gray-300 text-gray-700 rounded px-4 py-2 font-semibold transition-all duration-100 ease-in hover:bg-gray-400 hover:text-gray-800 mr-2">
            Daftar
          </nuxt-link>
          <nuxt-link to="/auth/login" tag="a" class="bg-blue-400 text-gray-100 rounded px-4 py-2 font-semibold transition-all duration-100 ease-in hover:bg-blue-600 hover:text-gray-300">
            Masuk
          </nuxt-link>
        </div>
      </nav>
    </div>

    <!-- section -->
    <section class="container mx-auto px-12">
      <div class="flex flex-row flex-grow">
        <div class="w-1/2 self-center pr-20 pb-12">
          <h1 class="text-6xl text-gray-700 leading-none">
            Bursa Kerja Khusus
          </h1>
          <hr class="tw-hr lg hidden md:block">
          <div class="text-gray-700 mt-2 ml-1">
            Situs web Bursa Kerja Khusus untuk mempertemukan para pekerja lulusan smk dengan perusahaan pencari kerja.
          </div>
          <div class="mt-4">
            <Button text="Cari Kerja" type="primary" />
            <Button text="Masuk" type="transparant" />
          </div>
        </div>
        <div class="w-1/2 self-center text-right">
          <img src="~/assets/images/illustrations/1.svg" alt="Illustration Image">
        </div>
      </div>
    </section>

    <!-- section:footer -->
    <section class="bg-blue-700">
      <div class="container mx-auto p-4">
        <div class="flex flex-wrap">
          <div class="w-full md:w-1/2 self-center">
            <h2 class="font-semibold text-4xl mb-8 text-gray-100 py-20 pr-32">
              Bursa Kerja Khusus <br>
              SMKN 1 MOJOKERTO
            </h2>
          </div>
          <div class="w-full md:w-1/2 self-center p-2 md:p-10">
            <div class="bg-gray-100 shadow-xl rounded p-8">
              <h3 class="font-semibold text-2xl mb-2 text-gray-800">
                Lorem ipsum dolor sit amet.
              </h3>
              <p>
                Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptate dolor maxime, possimus architecto neque repellendus cumque, pariatur, quam non delectus incidunt porro corporis! Incidunt a adipisci nesciunt quia suscipit optio!
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="bg-blue-600">
        <div class="bg-blue-700 text-center p-2">
          <span class="text-gray-200">
            &copy; <a href="#" class="font-semibold">D-IT Soft</a> 2020. All rights reserved. BKK 1.0 and
            made with
            <div class="inline-block">
              <svg xmlns="http://www.w3.org/2000/svg" width="14" height="13" viewBox="0 0 14 13">
                <path fill="#F56565" fill-rule="nonzero" d="M13.59 1.778c-.453-.864-3.295-3.755-6.59.431C3.54-1.977.862.914.41 1.778c-.825 1.596-.33 4.014.823 5.18L7.001 13l5.767-6.043c1.152-1.165 1.647-3.582.823-5.18z" />
              </svg>
            </div>
          </span>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
import Button from '../components/Button'
export default {
  components: { Button },
  head: {
    title: 'Home'
  }
}
</script>
