<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="e4250bc1n"/><path class="cs9mcsyng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:speedrun-timer" /></template>
<style>
.cs9mcsyng {
  d: path("M12.75 2.75h4m-2 0V7m0 6.5V10m-12 .5h3m-3 3h3m-3 3h3");
}

.e4250bc1n {
  cx: 14.75px;
  cy: 13.5px;
  r: 6.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
