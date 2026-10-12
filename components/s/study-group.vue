<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="wv5f_1brg"/><circle class="lth1vpd0k"/><circle class="z4na1z2mr"/><path class="u1b6yhbql"/><path class="fa14u7bwf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:study-group" /></template>
<style>
.fa14u7bwf {
  d: path("M12 13.25c-1.6-1-3.6-1.25-5.25-1v7.5c1.65-.25 3.65 0 5.25 1c1.6-1 3.6-1.25 5.25-1v-7.5c-1.65-.25-3.65 0-5.25 1m0 0v7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lth1vpd0k {
  cx: 5.25px;
  cy: 8.75px;
  r: 2px;
}

.u1b6yhbql {
  d: path("M2.75 16.25v-.5A3 3 0 0 1 7 13m14.25 3.25v-.5A3 3 0 0 0 17 13");
}

.wv5f_1brg {
  cx: 12px;
  cy: 5.25px;
  r: 2.5px;
}

.z4na1z2mr {
  cx: 18.75px;
  cy: 8.75px;
  r: 2px;
}

</style>
