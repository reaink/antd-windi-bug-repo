<template>
  <img class="mx-auto pt-16" alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3 + TypeScript + Vite + AntDesignVue + WindiCSS" />
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import HelloWorld from './components/HelloWorld.vue'

export default defineComponent({
  name: 'App',
  components: {
    HelloWorld
  }
})
</script>

<style>
#app {
  @apply text-center font-sans;
}
</style>
