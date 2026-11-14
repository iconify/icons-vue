<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="afm0rdbym"/><path class="nu66edblv"/><path class="h_1b_fbrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:voice-record" /></template>
<style>
.afm0rdbym {
  d: path("M8 2.5h4a1.25 1.25 0 0 1 1.25 1.25v8.5A1.25 1.25 0 0 1 12 13.5H8a1.25 1.25 0 0 1-1.25-1.25v-8.5A1.25 1.25 0 0 1 8 2.5Z");
}

.h_1b_fbrl {
  fill: currentColor;
  d: path("M17 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.nu66edblv {
  d: path("M4 10.5v.5a6 6 0 0 0 12 0v-.5M10 17v4.5m-3 0h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
