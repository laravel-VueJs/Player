<script setup>

</script>
<template>
  <div class="course-player overflow-auto sm:w-full lg:w-[calc(100%-var(--sidebar-width))] lg:h-[calc(100vh-var(--nav-height))] p-5">
    <div class=" ">
      <div class="episode-info mb-4 flex justify-between items-center">
        <h1 class="text-xl">Getting Started with Vue.js</h1>
        <div class="episode-nav">
          <div class="sm:hidden xl:inline-flex">
            <a class="bg-sky-500 hover:bg-sky-600 text-white mr-2 font-medium py-2 px-6 rounded">Download Resource</a>

            <button class="bg-gray-300 hover:bg-gray-400 text-gray-800 w-30 font-medium py-2 px-6 rounded-l">Completed</button>
            <div class="w-[1px] bg-gray-400"></div>
            <button class="mr-2 bg-gray-300 hover:bg-gray-400 text-gray-800 w-32 font-medium py-22 px-6 rounded-r">Bookmark</button>
            <!-- <button class="mr-2 bg-gray-300 hover:bg-gray-400 text-gray-800 w-34 font-medium py-22 px-6 rounded-r">
                                    Unbookmark
                                </button> -->

            <button class="bg-gray-300 hover:bg-gray-400 text-gray-800 w-28 font-medium py-2 px-6 rounded-l">Previous</button>
            <div class="w-[1px] bg-gray-400"></div>
            <button class="bg-gray-300 hover:bg-gray-400 text-gray-800 w-28 font-medium py-22 px-6 rounded-r">Next</button>
          </div>
          <div class="sm:inline-flex xl:hidden">
            <button class="bg-sky-500 hover:bg-sky-600 text-white mr-2 font-medium py-2 px-6 rounded">Resource</button>
            <button  class="bg-gray-300 hover:bg-gray-400 text-gray-800 w-16 font-medium py-2 px-2 rounded-l">Prev</button>
            <div class="w-[1px] bg-gray-400"></div>
            <button  class="bg-gray-300 hover:bg-gray-400 text-gray-800 w-16 font-medium py-22 px-2 rounded-r">Next</button>
          </div>
        </div>
      </div>
      <div>
        <iframe class="w-full aspect-video" src="https://www.youtube.com/embed/h9BtIWekM7s?si=0q0rEu6eCrb1bi4k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
      </div>
    </div>
  </div>
</template>

<style scoped>
</style>