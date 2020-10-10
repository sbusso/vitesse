<template>
  <nav class="flex flex-wrap items-center justify-between">
    <div class="mt-2 text-4xl">
      <Icon class="inline-block iconify" icon="carbon:campsite" />

      <a class="pt-1" href="https://github.com/sbusso/vitesse" target="_blank">
        Vitesse
      </a>
    </div>
    <ul class="flex">
      <li class="mt-1 mr-6">
        <a href="#">Link 1</a>
      </li>
      <li class="mt-1 mr-6">
        <a href="#">link 2</a>
      </li>
      <li>
        <a
          href="#"
          class="block inline-block px-4 py-2 mr-4 text-sm leading-none text-gray-600 border border-gray-600 rounded hover:border-transparent hover:text-teal-500 hover:bg-white lg:mt-0 lg:inline-block"
        >Login</a>
      </li>
    </ul>
  </nav>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  setup() {
    return {}
  },
})
</script>
