<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="pfpt48slt"/><path class="mwt9g9byc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:saturn-ring" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mwt9g9byc {
  d: path("M21.16 8.67a9.75 2.5-20 1 1-18.32 6.66");
}

.pfpt48slt {
  cx: 12px;
  cy: 12px;
  r: 5.5px;
}

</style>
