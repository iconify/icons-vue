<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v9io5-o5y"/><circle class="bgi7r_bab"/><path class="ds6-36beq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:violin" /></template>
<style>
.bgi7r_bab {
  cx: 17.43px;
  cy: 4.86px;
  r: 1.25px;
}

.ds6-36beq {
  d: path("m10.22 14.84l-1 1.73m3.16-.48l-1 1.73M3 13.5l18 7.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v9io5-o5y {
  d: path("M14.05 10.7c2.38 1.38 2.31 2.49 1.61 3.7c-.5.87-1.83.68-2.33 1.54c-.45.78 1.03 2.22.18 3.69c-.8 1.38-2.8 1.26-4.71.16s-3.01-2.78-2.21-4.16c.85-1.47 2.83-.91 3.28-1.69c.5-.86-.33-1.92.17-2.79c.7-1.21 1.63-1.82 4.01-.45m0 0l2.75-4.76");
}

</style>
