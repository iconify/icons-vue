<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="fhcsjwttb"/><path class="e9--qhy1m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sleep-timer" /></template>
<style>
.e9--qhy1m {
  d: path("M9.75 2.75h4.5m-2.25 0v3m0 3.5a3.1 3.1 0 0 0 4.25 4.25A4.25 4.25 0 1 1 12 9.25");
}

.fhcsjwttb {
  cx: 12px;
  cy: 13.5px;
  r: 7.75px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
