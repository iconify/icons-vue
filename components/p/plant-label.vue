<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r97nb_b-i"/><path class="q6vwp3b6n"/><path class="r0p1macpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plant-label" /></template>
<style>
.q6vwp3b6n {
  d: path("M6.25 7.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.r0p1macpf {
  fill: currentColor;
  d: path("M10.75 14.75c0-2.5 1.5-4 4-4c0 2.5-1.5 4-4 4Z");
}

.r97nb_b-i {
  d: path("M3 3h8.5l9.5 9.5l-8.5 8.5L3 11.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
