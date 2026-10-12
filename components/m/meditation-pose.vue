<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vx18d8c_y"/><circle class="u782pnb2p"/><path class="d9l29mv2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:meditation-pose" /></template>
<style>
.d9l29mv2g {
  d: path("M12 10.5v4m-4.25 0L12 11l4.25 3.5m-12.5 4.25c0-1.6 3.7-2.75 8.25-2.75s8.25 1.15 8.25 2.75a2.25 2.25 0 0 1-2.25 2.5H6a2.25 2.25 0 0 1-2.25-2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u782pnb2p {
  cx: 12px;
  cy: 7.25px;
  r: 1.75px;
}

.vx18d8c_y {
  d: path("M5 10a7 7 0 0 1 14 0");
}

</style>
