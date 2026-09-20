<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k628-abaf"/><path class="lh7nxd5dq"/><path class="ji-xh3b0v"/><path class="z7yjp67_f"/><path class="q4bb_8bsv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:refund-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ji-xh3b0v {
  d: path("M8 10.5v3");
}

.k628-abaf {
  fill: currentColor;
  d: path("M3 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.lh7nxd5dq {
  d: path("M3 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.q4bb_8bsv {
  d: path("M21.5 9.5 19 12l2.5 2.5");
}

.z7yjp67_f {
  d: path("M18 9.5 15.5 12l2.5 2.5");
}

</style>
