<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ksiibsbdf"/><path class="aq-kx-fco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shift-schedule" /></template>
<style>
.aq-kx-fco {
  d: path("M3.75 10h16.5M8 2.75v4.5m8-4.5v4.5M7.25 13.5h5.5m-1.5 3.25h5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ksiibsbdf {
  width: 16.5px;
  height: 15px;
  x: 3.75px;
  y: 5.25px;
  rx: 2.5px;
}

</style>
