<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j7-cbbc4y"/><path class="n-6_m9bzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pixel-launcher" /></template>
<style>
.j7-cbbc4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.854 4.5H10.816v39h8.633V31.16h4.405c7.362 0 13.33-5.968 13.33-13.33S31.217 4.5 23.855 4.5");
}

.n-6_m9bzo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.449 12.955h4.349a4.896 4.896 0 0 1 4.894 4.894h0a4.896 4.896 0 0 1-4.894 4.894h-4.35zm0 0L10.816 4.5m8.633 18.243l-8.633 7.056m17.545-13.718l6.63-5.578m-1.246 16.264l-6.125-5.863");
}

</style>
