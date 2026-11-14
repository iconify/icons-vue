<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cesrzwioj"/><path class="nrbn43b1r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smart-display" /></template>
<style>
.cesrzwioj {
  d: path("M7.875 2.5h8.25A4.375 4.375 0 0 1 20.5 6.875v6.75A4.375 4.375 0 0 1 16.125 18h-8.25A4.375 4.375 0 0 1 3.5 13.625v-6.75A4.375 4.375 0 0 1 7.875 2.5M12 18v3.5m-3.5 0h7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nrbn43b1r {
  d: path("M8 5.25h8A1.75 1.75 0 0 1 17.75 7v6.5A1.75 1.75 0 0 1 16 15.25H8a1.75 1.75 0 0 1-1.75-1.75V7A1.75 1.75 0 0 1 8 5.25");
}

</style>
