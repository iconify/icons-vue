<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kkk6usbfw"/><path class="cdriyqbij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:measure-mass" /></template>
<style>
.cdriyqbij {
  d: path("M8.25 14.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m3.75 0l2.25-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kkk6usbfw {
  d: path("M7.375 7.5h9.25A4.375 4.375 0 0 1 21 11.875v5.25a4.375 4.375 0 0 1-4.375 4.375h-9.25A4.375 4.375 0 0 1 3 17.125v-5.25A4.375 4.375 0 0 1 7.375 7.5M3.5 3.5h17m-8.5 0v4");
}

</style>
