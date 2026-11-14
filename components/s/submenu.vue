<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dt7alwbag"/><path class="leuncbb1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:submenu" /></template>
<style>
.dt7alwbag {
  d: path("M10.2 16.5H2.5v-14h13v8.7M5.25 6H8.5M5.25 9.5H8.5M5.25 13H8.5");
}

.leuncbb1o {
  d: path("m11 7.75l1.75 1.75L11 11.25M13 14h8.5v7.5H13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
