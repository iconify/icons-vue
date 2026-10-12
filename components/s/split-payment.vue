<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="q0_gb6qzx"/><path class="wxui75sux"/><rect class="cwjx07j6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:split-payment" /></template>
<style>
.cwjx07j6k {
  width: 3.25px;
  height: 2.75px;
  x: 5.25px;
  y: 11.5px;
  rx: 0.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q0_gb6qzx {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 5.25px;
  rx: 2px;
}

.wxui75sux {
  d: path("M2.75 8.75h18.5m-6.75-3.5l-5 13.5");
}

</style>
