<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p2gp6fbnl"/><path class="h2-7d6b0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-drop" /></template>
<style>
.h2-7d6b0r {
  d: path("M9.75 11.5A2.25 2.25 0 0 0 12 13.75M3.5 18c1.5 3 15.5 3 17 0");
}

.p2gp6fbnl {
  d: path("M12 2.5s-5 5.5-5 9a5 5 0 0 0 10 0c0-3.5-5-9-5-9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
