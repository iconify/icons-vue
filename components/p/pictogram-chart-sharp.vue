<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="xhnw9ebpu"/><path class="kru1u5bgs"/><circle class="p98yu_b-b"/><path class="qpzb6tiaz"/><circle class="r7064rbil"/><path class="k4s9kntlm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pictogram-chart-sharp" /></template>
<style>
.k4s9kntlm {
  d: path("M16.75 18.5v-4.75a2.25 2.25 0 0 1 4.5 0v5.75h-4.5z");
}

.kru1u5bgs {
  d: path("M2.75 18.5v-4.75a2.25 2.25 0 0 1 4.5 0v5.75h-4.5z");
}

.p98yu_b-b {
  cx: 12px;
  cy: 7.75px;
  r: 1.75px;
}

.qpzb6tiaz {
  d: path("M9.75 18.5v-4.75a2.25 2.25 0 0 1 4.5 0v5.75h-4.5z");
}

.r7064rbil {
  cx: 19px;
  cy: 7.75px;
  r: 1.75px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xhnw9ebpu {
  cx: 5px;
  cy: 7.75px;
  r: 1.75px;
}

</style>
