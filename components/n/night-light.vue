<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f8jpv1nbu"/><path class="n7db0obac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:night-light" /></template>
<style>
.f8jpv1nbu {
  d: path("M9 18v-1.5c-3-1.5-4.5-4-4.5-7a7.5 7.5 0 0 1 15 0c0 3-1.5 5.5-4.5 7V18Zm.5 3h5");
}

.n7db0obac {
  d: path("M13 5.5a4.25 4.25 0 1 0 3 7a3.5 3.5 0 0 1-3-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
