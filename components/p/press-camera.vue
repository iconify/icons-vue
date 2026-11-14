<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="y0a1zvupm"/><path class="rstz894zu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:press-camera" /></template>
<style>
.rstz894zu {
  d: path("M8.75 14.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM6.5 2.5V5m-4-.75l1.25 1.5m6.75-1.5l-1.25 1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y0a1zvupm {
  d: path("M2.5 8.5h19v12h-19Zm12.5 0v-2h4v2");
}

</style>
