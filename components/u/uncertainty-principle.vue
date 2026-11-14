<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="efemxqbfw"/><path class="yf8cjudbl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:uncertainty-principle" /></template>
<style>
.efemxqbfw {
  d: path("M3 3v18h18m-8-10.5h.01m1.871-5.168a5.5 5.5 0 0 1 3.287 3.287");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yf8cjudbl {
  d: path("M18.168 12.381a5.5 5.5 0 0 1-3.287 3.287m-3.762 0a5.5 5.5 0 0 1-3.287-3.287m0-3.762a5.5 5.5 0 0 1 3.287-3.287");
}

</style>
