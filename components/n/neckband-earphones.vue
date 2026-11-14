<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fja47rb1a"/><path class="ox61--bau"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:neckband-earphones" /></template>
<style>
.fja47rb1a {
  d: path("M5.5 6v6a6.5 6.5 0 0 0 13 0V6");
}

.ox61--bau {
  d: path("M3.5 2.5h4V7h-4Zm13 0h4V7h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
