<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="a_v25oq5v"/><path class="mb2nr6bcq"/><circle class="tbv1ubc9c"/><circle class="jksu-ji1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:refrigerated-truck" /></template>
<style>
.a_v25oq5v {
  width: 11.5px;
  height: 10.5px;
  x: 2.75px;
  y: 4.5px;
  rx: 1.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jksu-ji1z {
  cx: 19px;
  cy: 19.25px;
  r: 1.5px;
}

.mb2nr6bcq {
  d: path("M8.5 9.75V7.5m0 2.25V12m0-2.25L6.55 8.63M8.5 9.75l1.95 1.13M8.5 9.75l-1.95 1.13M8.5 9.75l1.95-1.12m6.3 5.37V9q0-1 1-1H18q1 0 1.6.8l1.05 1.4q.6.8.6 1.8v2q0 1-1 1h-2.5q-1 0-1-1m-2.5-.5h2.5");
}

.tbv1ubc9c {
  cx: 6.5px;
  cy: 19.25px;
  r: 1.5px;
}

</style>
