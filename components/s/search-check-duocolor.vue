<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uhud8lsud"/><path class="vy7vn8b1q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:search-check-duocolor" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uhud8lsud {
  stroke-opacity: 0.4;
  d: path("m7 10l2 2l4-4");
}

.vy7vn8b1q {
  d: path("M3 10a7 7 0 1 0 14 0a7 7 0 0 0-14 0m12 5l6 6");
}

</style>
