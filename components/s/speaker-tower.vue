<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nx4thubkq"/><path class="o61kau_gh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:speaker-tower" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nx4thubkq {
  d: path("M11.375 2.5h1.25A4.375 4.375 0 0 1 17 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-1.25A4.375 4.375 0 0 1 7 17.125V6.875A4.375 4.375 0 0 1 11.375 2.5M12 6h.01M12 9.75h.01");
}

.o61kau_gh {
  d: path("M9 15.75a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
