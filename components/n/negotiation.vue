<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sl3p_uboo"/><path class="tyzcd1bdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:negotiation" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sl3p_uboo {
  d: path("M4.75 2.75h7a2 2 0 0 1 2 2V9a2 2 0 0 1-2 2H7.5l-3 2.5v-2.6a2 2 0 0 1-1.75-2V4.75a2 2 0 0 1 2-2");
}

.tyzcd1bdn {
  d: path("M5.75 6.9h5M9 5.15l1.75 1.75L9 8.65M19.25 11h-2a3.5 3.5 0 0 1-3.5 3.5h-2a2 2 0 0 0-2 2a2 2 0 0 0 2 2h4.5l3 2.5v-2.6a2 2 0 0 0 2-2V13a2 2 0 0 0-2-2");
}

</style>
