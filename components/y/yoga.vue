<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="xe53owbmy"/><path class="dat_poxlx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:yoga" /></template>
<style>
.dat_poxlx {
  d: path("M4.25 11.5L8.5 13L12 9.5l3.5 3.5l4.25-1.5M12 9.5v6m-7.75 3.75c0-1.75 3.5-3 7.75-3s7.75 1.25 7.75 3a1.5 1.5 0 0 1-1.5 1.5H5.75a1.5 1.5 0 0 1-1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xe53owbmy {
  cx: 12px;
  cy: 5px;
  r: 2px;
}

</style>
