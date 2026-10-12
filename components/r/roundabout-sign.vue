<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="dbgvcxwad"/><path class="q2as53aib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:roundabout-sign" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q2as53aib {
  d: path("M13.23 7.41A4.75 4.75 0 0 1 16.75 12m1.5-1.6l-1.5 1.6l-1.5-1.6m.11 4.96a4.75 4.75 0 0 1-5.73.75m.63 2.1l-.63-2.1l2.13-.5m-4.35-2.38a4.75 4.75 0 0 1 2.21-5.34m-2.13-.5l2.13.5l-.63 2.1");
}

</style>
