<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lagtfvtzq"/><path class="z7428wbeg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:swim-trunks" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lagtfvtzq {
  width: 15.5px;
  height: 3px;
  x: 4.25px;
  y: 3.25px;
  rx: 1.25px;
}

.z7428wbeg {
  d: path("M5.75 8.5h12.5q1.25 0 1.46 1.23l1.33 8.04q.21 1.23-1.02 1.44l-5.04.83q-1.23.21-1.59-.99l-1.03-3.35q-.36-1.2-.72 0l-1.03 3.35q-.36 1.2-1.59.99l-5.04-.83Q2.75 19 2.96 17.77l1.33-8.04Q4.5 8.5 5.75 8.5m5-2.25l-.75 4.5m3.25-4.5l.75 4.5");
}

</style>
