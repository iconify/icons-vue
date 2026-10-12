<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lkve0tb3s"/><path class="zxa3sv3va"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:upscale-ai" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lkve0tb3s {
  width: 8px;
  height: 8px;
  x: 2.75px;
  y: 13.25px;
  rx: 2px;
}

.zxa3sv3va {
  d: path("M6.75 13.25v8m-4-4h8M10 2.75h8.75a2.5 2.5 0 0 1 2.5 2.5V14m-8.5-2.75l5.5-5.5m-4.5 0h4.5v4.5");
}

</style>
