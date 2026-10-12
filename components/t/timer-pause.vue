<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="fhcsjwttb"/><path class="aow7hm07i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:timer-pause" /></template>
<style>
.aow7hm07i {
  d: path("M9.75 2.75h4.5m-2.25 0v3M17.5 8l1.75-1.75m-9 4.75v5m3.5-5v5");
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
