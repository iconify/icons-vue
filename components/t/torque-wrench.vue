<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wzmpwobhr"/><circle class="xc7q9zb4s"/><path class="py2-63mnj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:torque-wrench" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.py2-63mnj {
  d: path("m11.47 18.34l1.1-1.1");
}

.wzmpwobhr {
  d: path("M17.39 3.97a5.08 5.08 0 0 0-6.57 6.94l-6.8 6.8a1.6 1.6 0 0 0 2.27 2.27l6.8-6.8a5.08 5.08 0 0 0 6.94-6.57l-3.34 3.35l-2.65-2.65Z");
}

.xc7q9zb4s {
  cx: 11.47px;
  cy: 18.34px;
  r: 2.5px;
}

</style>
