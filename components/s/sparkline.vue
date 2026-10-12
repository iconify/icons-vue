<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="h5_ol53lx"/><path class="cuhmvlbkj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sparkline" /></template>
<style>
.cuhmvlbkj {
  d: path("m6.25 13.75l2.5-2.5l2.5 2l3-4.5l3.5 3");
}

.h5_ol53lx {
  width: 18.5px;
  height: 12.5px;
  x: 2.75px;
  y: 5.75px;
  rx: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
