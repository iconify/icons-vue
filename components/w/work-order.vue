<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cj_gqbbkp"/><path class="w51xkkb9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:work-order" /></template>
<style>
.cj_gqbbkp {
  d: path("M2.5 4.5h19V10a2 2 0 0 0 0 4v5.5h-19V14a2 2 0 0 0 0-4Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w51xkkb9x {
  d: path("M12.47 8.653a2 2 0 1 1-1.623-1.623M5.75 15.25L9 11m7-4.5V8m0 3.25v1.5M16 16v1.5");
}

</style>
