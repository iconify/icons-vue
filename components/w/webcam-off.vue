<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="o8w52mbli"/><circle class="t8ttqnb2f"/><path class="mlvjywbib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:webcam-off" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mlvjywbib {
  d: path("M12 16.75v4.5m-4.25 0h8.5");
}

.o8w52mbli {
  cx: 12px;
  cy: 9.75px;
  r: 7px;
}

.t8ttqnb2f {
  cx: 12px;
  cy: 9.75px;
  r: 3px;
}

</style>
