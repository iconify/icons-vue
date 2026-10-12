<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ffqh_krzg"/><circle class="pdtmnk8rt"/><circle class="n81udiknj"/><circle class="eksewbbze"/><circle class="qll10k7wy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:plot-boundary" /></template>
<style>
.eksewbbze {
  cx: 19.5px;
  cy: 19.5px;
  r: 1.5px;
}

.ffqh_krzg {
  d: path("m7.4 6.1l2.9-.4m2.9-.4l2.9-.4m3 2.6l.1 3m.1 3l.1 3m-2.7 2.8l-2.8-.2m-2.8-.2l-2.8-.2m-3-2.6l-.2-2.4m-.2-2.4l-.2-2.4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n81udiknj {
  cx: 19px;
  cy: 4.5px;
  r: 1.5px;
}

.pdtmnk8rt {
  cx: 4.5px;
  cy: 6.5px;
  r: 1.5px;
}

.qll10k7wy {
  cx: 5.5px;
  cy: 18.5px;
  r: 1.5px;
}

</style>
