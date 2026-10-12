<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="wv5f_1brg"/><path class="rdh83ub8v"/><rect class="ujbx53xlj"/><path class="twcm1ab_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stamp-check" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rdh83ub8v {
  d: path("M10.5 7.75v3.75m3-3.75v3.75");
}

.twcm1ab_o {
  d: path("M4.75 20.5h14.5");
}

.ujbx53xlj {
  width: 16.5px;
  height: 5px;
  x: 3.75px;
  y: 11.5px;
  rx: 1.5px;
}

.wv5f_1brg {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

</style>
