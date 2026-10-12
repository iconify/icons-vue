<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="djrfyyy1p"/><path class="k8574nm4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:presentation-remote" /></template>
<style>
.djrfyyy1p {
  width: 9.5px;
  height: 14px;
  x: 7.25px;
  y: 7.25px;
  rx: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k8574nm4j {
  d: path("M9.75 12.25L12 10l2.25 2.25m-4.5 4L12 18.5l2.25-2.25m-5-12a4 4 0 0 1 5.5 0");
}

</style>
