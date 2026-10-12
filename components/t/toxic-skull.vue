<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cmdt0kehn"/><circle class="ayqgw4bzo"/><circle class="hmtrbg1-p"/><path class="hfceukh5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toxic-skull" /></template>
<style>
.ayqgw4bzo {
  cx: 8.75px;
  cy: 10.5px;
  r: 2px;
}

.cmdt0kehn {
  d: path("M4.25 10.5C4.25 6 7.75 3 12 3s7.75 3 7.75 7.5V13l-2.25 1.75v1.5h-11v-1.5L4.25 13Z");
}

.hfceukh5d {
  d: path("M9 17.25c1 1.1 1.5 2 1.5 2.5a1.5 1.5 0 0 1-3 0c0-.5.5-1.4 1.5-2.5m6 0c1 1.1 1.5 2 1.5 2.5a1.5 1.5 0 0 1-3 0c0-.5.5-1.4 1.5-2.5");
}

.hmtrbg1-p {
  cx: 15.25px;
  cy: 10.5px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
