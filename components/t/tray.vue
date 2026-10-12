<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="bm2oed1qf"/><path class="hhv4p858a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tray" /></template>
<style>
.bm2oed1qf {
  width: 5px;
  height: 5.25px;
  x: 5.25px;
  y: 8.5px;
  rx: 1.5px;
}

.hhv4p858a {
  d: path("M14.25 7h3.5q1 0 .89.99l-.53 4.77q-.11.99-1.11.99h-2q-1 0-1.11-.99l-.53-4.77q-.11-.99.89-.99m-11.5 9.25h18.5l-1.4 2.8a2 2 0 0 1-1.8 1.2H5.95a2 2 0 0 1-1.8-1.2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
