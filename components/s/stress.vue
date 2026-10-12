<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eqgjd28gw"/><circle class="qi0czrdcc"/><path class="kvsxdhb9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stress" /></template>
<style>
.eqgjd28gw {
  d: path("M4.75 5.5L7.17 3l2.41 2.5L12 3l2.42 2.5L16.83 3l2.42 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kvsxdhb9c {
  d: path("M5 21.25h14a1 1 0 0 0 1-1c0-2.6-3.6-4.5-8-4.5s-8 1.9-8 4.5a1 1 0 0 0 1 1");
}

.qi0czrdcc {
  cx: 12px;
  cy: 10.5px;
  r: 3px;
}

</style>
