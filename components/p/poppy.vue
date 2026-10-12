<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g28e5pb7f"/><circle class="unmjjutjp"/><path class="c95hiub6p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:poppy" /></template>
<style>
.c95hiub6p {
  d: path("M12 15.25q0 3.375 2.25 6");
}

.g28e5pb7f {
  d: path("M4.25 7.5c1.5-1 3.25-1 4.5 0c.5-1.25 1.75-2 3.25-2s2.75.75 3.25 2c1.25-1 3-1 4.5 0c0 4.5-3.5 7.75-7.75 7.75S4.25 12 4.25 7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.unmjjutjp {
  cx: 12px;
  cy: 10px;
  r: 1.75px;
}

</style>
