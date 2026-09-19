<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="km57rgbje"/><path class="m9hp1jb4j"/><path class="hp-7e7b4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:retouche-photo" /></template>
<style>
.hp-7e7b4v {
  d: path("M28.354 14.294a7.602 7.602 0 1 1-.167-.187");
}

.km57rgbje {
  d: path("M39.047 5.36a2.479 2.479 0 1 1-.054-.06M15.121 31.478V43.5l-6.77-3.856V18.161");
}

.m9hp1jb4j {
  d: path("M8.358 18.378a14.267 14.267 0 1 1 6.816 13.063");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
