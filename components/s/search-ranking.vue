<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w7v1zgbmc"/><path class="vf_wwj37x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:search-ranking" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vf_wwj37x {
  d: path("M9.25 8.5L11 7.25V14");
}

.w7v1zgbmc {
  d: path("M3 10.5a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Zm12.75 5.25L21 21");
}

</style>
