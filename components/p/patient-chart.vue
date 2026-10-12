<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ucgfdnb2k"/><path class="ekej6zu6x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:patient-chart" /></template>
<style>
.ekej6zu6x {
  d: path("M9 5.5V3.75a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1V5.5Zm-1 4h8m-8 3h5m-5.25 4h2L11 14l1.5 4l1.25-2.5h2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ucgfdnb2k {
  width: 14.5px;
  height: 15.75px;
  x: 4.75px;
  y: 5.5px;
  rx: 2px;
}

</style>
