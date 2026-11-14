<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jo1h5-i7i"/><path class="to1-mnhfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:query-parameters" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jo1h5-i7i {
  d: path("M6.875 3.5h10.25A4.375 4.375 0 0 1 21.5 7.875v8.25a4.375 4.375 0 0 1-4.375 4.375H6.875A4.375 4.375 0 0 1 2.5 16.125v-8.25A4.375 4.375 0 0 1 6.875 3.5M2.5 8h19M6 12.5h1.75");
}

.to1-mnhfv {
  d: path("M11.75 10.75h1.5A1.75 1.75 0 0 1 15 12.5a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 10 12.5a1.75 1.75 0 0 1 1.75-1.75m5.5 1.75H18M6 16.75h7");
}

</style>
