<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="zy82-wb5i"/><circle class="o-c0s6bzg"/><path class="t2lspobpz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:no-drones" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o-c0s6bzg {
  cx: 6.5px;
  cy: 17.5px;
  r: 2.25px;
}

.t2lspobpz {
  d: path("M15.91 8.09L15 9m-6.91 6.91L9 15m3.18-6H15v2.82M11.82 15H9v-2.82M3.75 3.75l16.5 16.5");
}

.zy82-wb5i {
  cx: 17.5px;
  cy: 6.5px;
  r: 2.25px;
}

</style>
