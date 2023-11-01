<template>
  <div>
    <!-- <NuxtImg preload src="/placeholder.png" /> -->
    <div class="flex flex-wrap gap-4 p-4 justify-center">
        <NuxtImg class="w-1/4" src="https://images.pexels.com/photos/3755706/pexels-photo-3755706.jpeg"  :placeholder="[30, 20]"/>
        <NuxtImg class="w-1/4" width="300" height="200" :placeholder="[30, 20]" src="https://images.unsplash.com/photo-1464822759023-fed622ff2c3b" sizes="100vw sm:50vw md:400px"  loading="lazy"/>
        <NuxtImg class="w-1/4" width="300" height="200" :placeholder="[30, 20]" src="https://images.pexels.com/photos/1402787/pexels-photo-1402787.jpeg"   loading="lazy"/>
        <NuxtImg class="w-1/4" width="300" height="200" :placeholder="[30, 20]" src="https://images.pexels.com/photos/50594/sea-bay-waterfront-beach-50594.jpeg" sizes="100vw sm:50vw md:400px"  loading="lazy"/>
        <NuxtImg class="w-1/4" width="300" height="200" :placeholder="[30, 20]" src="https://images.pexels.com/photos/36487/above-adventure-aerial-air.jpg" sizes="100vw sm:50vw md:400px"  loading="lazy"/>
        <NuxtImg class="w-1/4" width="300" height="200" :placeholder="[30, 20]" src="https://images.pexels.com/photos/443446/pexels-photo-443446.jpeg" sizes="100vw sm:50vw md:400px"  loading="lazy"/>
        <NuxtImg class="w-1/4" width="300" height="200" :placeholder="[30, 20]" src="https://images.pexels.com/photos/884788/pexels-photo-884788.jpeg" sizes="100vw sm:50vw md:400px"  loading="lazy"/>
        <NuxtImg class="w-1/4" width="300" height="200" :placeholder="[30, 20]" src="https://images.pexels.com/photos/534164/pexels-photo-534164.jpeg" sizes="100vw sm:50vw md:400px"  loading="lazy"/>
        <NuxtImg class="w-1/4" width="300" height="200" :placeholder="[30, 20]" src="https://images.pexels.com/photos/753626/pexels-photo-753626.jpeg" sizes="100vw sm:50vw md:400px"  loading="lazy"/>
        <NuxtImg class="w-1/4" width="300" height="200" :placeholder="[30, 20]" src="https://images.pexels.com/photos/395196/pexels-photo-395196.jpeg" sizes="100vw sm:50vw md:400px"  loading="lazy"/>
        <NuxtImg class="w-1/4" width="300" height="200" :placeholder="[30, 20]" src="https://images.pexels.com/photos/226424/pexels-photo-226424.jpeg" sizes="100vw sm:50vw md:400px"  loading="lazy"/>
        <NuxtImg class="w-1/4" width="300" height="200" :placeholder="[30, 20]" src="https://images.pexels.com/photos/1519088/pexels-photo-1519088.jpeg" sizes="100vw sm:50vw md:400px"  loading="lazy"/>
        <NuxtImg class="w-1/4" width="300" height="200" :placeholder="[30, 20]" src="https://images.pexels.com/photos/534049/pexels-photo-534049.jpeg" sizes="100vw sm:50vw md:400px"  loading="lazy"/>
        <NuxtImg class="w-1/4" width="300" height="200" :placeholder="[30, 20]" src="https://images.pexels.com/photos/33545/sunrise-phu-quoc-island-ocean.jpg" sizes="100vw sm:50vw md:400px"  loading="lazy"/>
    </div>

    <!-- <NuxtImg
      src="https://images.pexels.com/photos/3755706/pexels-photo-3755706.jpeg"
      :placeholder="[30, 20]"
      width="300"
      height="200"
      class="rounded"
    />

    <hr/>
    <NuxtPicture
      src="https://images.unsplash.com/photo-1465056836041-7f43ac27dcb5"
      sizes="xs:200px md:500px lg:1024"
      class="picture"
      width="800"
    />     -->


      <NuxtImg
        src="https://images.unsplash.com/photo-1465056836041-7f43ac27dcb5"
        :placeholder="[30,20]"
        width="300"
        height="200"
        class="rounded"
      />
    <!-- <figure>
      <NuxtPicture
        src="https://images.unsplash.com/photo-1465056836041-7f43ac27dcb5"
        width="800"
        height="600"
        sizes="xs:200px md:500px lg:1024"
      />
    </figure> -->


<div class="bg-white dark:bg-slate-800 rounded-lg px-6 py-8 ring-1 ring-slate-900/5 shadow-xl">
  <div>
    <span class="inline-flex items-center justify-center p-2 bg-indigo-500 rounded-md shadow-lg">
      <svg class="h-6 w-6 text-white" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" aria-hidden="true"><!-- ... --></svg>
    </span>
  </div>
  <h3 class="text-slate-900 dark:text-white mt-5 text-base font-medium tracking-tight">Writes Upside-Down</h3>
  <p class="text-slate-500 dark:text-slate-400 mt-2 text-sm">
    The Zero Gravity Pen can be used to write in any orientation, including upside-down. It even works in outer space.
  </p>
</div>

<div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8 pb-16 pt-20 text-center lg:pt-32">
  <h1 class="mx-auto max-w-4xl font-display text-5xl font-medium tracking-tight text-slate-900 sm:text-7xl">
    Accounting
    <span class="relative whitespace-nowrap text-blue-600">
      <svg aria-hidden="true" viewBox="0 0 418 42" class="absolute left-0 top-2/3 h-[0.58em] w-full fill-blue-300/70" preserveAspectRatio="none">
        <path d="M203.371.916c-26.013-2.078-76.686 1.963-124.73 9.946L67.3 12.749C35.421 18.062 18.2 21.766 6.004 25.934 1.244 27.561.828 27.778.874 28.61c.07 1.214.828 1.121 9.595-1.176 9.072-2.377 17.15-3.92 39.246-7.496C123.565 7.986 157.869 4.492 195.942 5.046c7.461.108 19.25 1.696 19.17 2.582-.107 1.183-7.874 4.31-25.75 10.366-21.992 7.45-35.43 12.534-36.701 13.884-2.173 2.308-.202 4.407 4.442 4.734 2.654.187 3.263.157 15.593-.78 35.401-2.686 57.944-3.488 88.365-3.143 46.327.526 75.721 2.23 130.788 7.584 19.787 1.924 20.814 1.98 24.557 1.332l.066-.011c1.201-.203 1.53-1.825.399-2.335-2.911-1.31-4.893-1.604-22.048-3.261-57.509-5.556-87.871-7.36-132.059-7.842-23.239-.254-33.617-.116-50.627.674-11.629.54-42.371 2.494-46.696 2.967-2.359.259 8.133-3.625 26.504-9.81 23.239-7.825 27.934-10.149 28.304-14.005.417-4.348-3.529-6-16.878-7.066Z"></path>
      </svg>
      <span class="relative">made simple</span>
    </span>
  </h1>
  <p class="mx-auto mt-6 max-w-2xl text-lg tracking-tight text-slate-700">Most bookkeeping software is accurate, but hard to use. We make the opposite trade-off, and hope you don’t get audited.</p>
  <div class="mt-10 flex justify-center gap-x-6">
    <a class="group inline-flex items-center justify-center rounded-full py-2 px-4 text-sm font-semibold focus:outline-none focus-visible:outline-2 focus-visible:outline-offset-2 bg-slate-900 text-white hover:bg-slate-700 hover:text-slate-100 active:bg-slate-800 active:text-slate-300 focus-visible:outline-slate-900" href="/register">Get 6 months free</a>
    <a class="group inline-flex ring-1 items-center justify-center rounded-full py-2 px-4 text-sm focus:outline-none ring-slate-200 text-slate-700 hover:text-slate-900 hover:ring-slate-300 active:bg-slate-100 active:text-slate-600 focus-visible:outline-blue-600 focus-visible:ring-slate-300" href="https://www.youtube.com/watch?v=dQw4w9WgXcQ">
      <svg aria-hidden="true" class="h-3 w-3 flex-none fill-blue-600 group-active:fill-current">
        <path d="m9.997 6.91-7.583 3.447A1 1 0 0 1 1 9.447V2.553a1 1 0 0 1 1.414-.91L9.997 5.09c.782.355.782 1.465 0 1.82Z"></path>
      </svg>
      <span class="ml-3">Watch video</span>
    </a>
  </div>

</div>

  </div>
</template>

<style scoped>
  img{
    object-fit: contain;
  }
</style>
