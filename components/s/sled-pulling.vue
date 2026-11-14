<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m7weq_6qb"/><path class="l62j1ib2n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sled-pulling" /></template>
<style>
.l62j1ib2n {
  d: path("M5.5 18v-4h7v4m3-5l4.75-6.75M18.5 4.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM2.5 21h19");
}

.m7weq_6qb {
  d: path("M3 18h12.5a2.5 2.5 0 0 0 0-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
