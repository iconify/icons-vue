<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="imk9_ib4g"/><circle class="zv2tbewos"/><path class="lzwztnbnn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:warranty-shield" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.imk9_ib4g {
  d: path("m11.3 2.95l-6.5 2.4a1.5 1.5 0 0 0-1 1.4V11c0 4.9 3.4 8.55 7.6 10.1a1.7 1.7 0 0 0 1.2 0c4.2-1.55 7.6-5.2 7.6-10.1V6.75a1.5 1.5 0 0 0-1-1.4l-6.5-2.4a2 2 0 0 0-1.4 0");
}

.lzwztnbnn {
  d: path("M12 9.5v1.75l1.25 1");
}

.zv2tbewos {
  cx: 12px;
  cy: 11.25px;
  r: 3.5px;
}

</style>
