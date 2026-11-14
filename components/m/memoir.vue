<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ca59bbccv"/><path class="y7o7tbcms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:memoir" /></template>
<style>
.ca59bbccv {
  d: path("M5 4.5a2 2 0 0 1 2-2h12v19H7a2 2 0 0 1-2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y7o7tbcms {
  d: path("M5 19.5A1.5 1.5 0 0 1 6.5 18H19M10.25 7a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-1.5 8a3.25 3.25 0 0 1 6.5 0");
}

</style>
