<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="t70xfobtt"/><path class="dse_opd3l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nebulizer" /></template>
<style>
.dse_opd3l {
  d: path("M8.25 12.25h7.5l-.85 6.9a2 2 0 0 1-2 1.85h-1.8a2 2 0 0 1-2-1.85Zm.25-5Q7.375 6.125 8.5 5c1.125-1.125.75-1.5 0-2.25m3.5 4.5Q10.875 6.125 12 5c1.125-1.125.75-1.5 0-2.25m3.5 4.5q-1.125-1.125 0-2.25c1.125-1.125.75-1.5 0-2.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t70xfobtt {
  width: 17.5px;
  height: 3px;
  x: 3.25px;
  y: 9.25px;
  rx: 1.25px;
}

</style>
