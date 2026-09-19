<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cp5kub62s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:telegram" /></template>
<style>
.cp5kub62s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.83 8.48c1.14 0 2 1 1.54 2.86l-5.58 26.3c-.39 1.87-1.52 2.32-3.08 1.45L20.4 29.26a.4.4 0 0 1 0-.65l15.37-13.88c.7-.62-.15-.92-1.07-.36L15.41 26.54a.46.46 0 0 1-.4.05L6.82 24C5 23.47 5 22.22 7.23 21.33L40 8.69a2.2 2.2 0 0 1 .83-.21");
}

</style>
