<template>
  <main>
    <section class="self-center flex flex-col flex-1 items-center justify-center">
      <h1 class="title text-center">Kadek Dodik Wirawan</h1>
      <h2 class="subtitle text-center">Fullstack Web Developer</h2>
      <p class="text-center">Hello! I’m Kadek Dodik Wirawan, a dedicated professional with a passion for excellence in website development and server management, live in Pemuteran, Buleleng, Bali, Indonesia.</p>
      <img src="https://kadekdodikwirawan.github.io/assets/img/hero-bg.JPG" class="cover-image">
    </section>

    <section class="mt-8">
      <h3 class="text-primary-600 dark:text-primary-400 max-w-5xl mx-auto">Latest blog post</h3>
      <posts post-type="blog" :amount="1" />
    </section>
  </main>
</template>