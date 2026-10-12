<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="cddhtmemy"/><path class="d78d0nb9y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:signature-delivery" /></template>
<style>
.cddhtmemy {
  width: 7.75px;
  height: 7px;
  x: 13.5px;
  y: 2.75px;
  rx: 1.25px;
}

.d78d0nb9y {
  d: path("M17.38 2.75v2m-14.63 16h18.5M3.5 17C5 12.5 7 9 8.25 10.5c1.1 1.4-2.25 5.75-.5 6.25c1.5.4 2.75-3.5 4-3.25c1.1.2.25 3 1.75 3.1c1 .05 1.75-1 2.5-1.6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
