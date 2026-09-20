<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d0swrnj3x"/><path class="j9ch-hj9y"/><path class="oa34-acln"/><path class="hc491gbyo"/><path class="x6_f3nb7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:storage-box-duotone-thin" /></template>
<style>
.d0swrnj3x {
  fill: currentColor;
  d: path("M3 6v4h18V6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hc491gbyo {
  d: path("M5 10v10h14V10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j9ch-hj9y {
  fill: currentColor;
  d: path("M10 14h4v3h-4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.oa34-acln {
  d: path("M3 6v4h18V6Z");
}

.x6_f3nb7s {
  d: path("M10 14h4v3h-4Z");
}

</style>
