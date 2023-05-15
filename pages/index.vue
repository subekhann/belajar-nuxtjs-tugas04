<template>
  <div class="p-4 background">
    <div>
      <h1
        class="text-2xl sm:text-3xl md:text-4xl lg:text-5xl xl:text-6xl text-center text-gray-800 dark:text-white font-black leading-7 md:leading-10"
      >
        Tutorial Meniup <span class="text-indigo-700">Gelembung </span>Ada
        Disini
      </h1>
      <p
        class="mt-5 sm:mt-10 lg:w-10/12 text-gray-400 font-normal text-center text-sm sm:text-lg mb-10"
      >
        Setelah berhasil mengajarkan Patrick Star untuk membuka toples
        dipertemuan sebelumnya, kali ini Spongebob akan berbagi tutorial lagi
        lhoo.. Berikut adalah tutorial meniup gelembung (by Spongebob S.)
      </p>
      <iframe
        width="560"
        height="315"
        src="https://www.youtube.com/embed/M-znyHDY1G4"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
        allowfullscreen
      ></iframe>
      <div>
        <NuxtLayout :name="layouts.index">
          <h1 class="font-semibold text-lg text-center text-indigo-700">
            Cek Layout
          </h1>
        </NuxtLayout>
      </div>
    </div>
  </div>
</template>

<style lang="postcss" scoped>
.background {
  @apply bg-gray-200;
}
.pisang {
  @apply text-blue-300;
}

.strawberries {
  @apply text-red-300;
}

.video {
  @apply text-red-300;
}

.html {
  color: #CF6B34;
}

.css {
  color: #D9657E;
}
</style>

<script>
export default {
  data() {
    return {
      layouts: {
        index: "index",
      },
    };
  },
};
</script>