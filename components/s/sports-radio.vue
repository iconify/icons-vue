<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h1sgffbvf"/><path class="t0qdf6img"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sports-radio" /></template>
<style>
.h1sgffbvf {
  d: path("M2.5 11.5h19V21h-19Zm4.25-5a7 7 0 0 1 10.5 0m-8 2a3.75 3.75 0 0 1 5.5 0");
}

.t0qdf6img {
  d: path("M14.5 16.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-8.5 0h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
