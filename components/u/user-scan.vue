<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="cey46ju5m"/><path class="r1_armb7o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-scan" /></template>
<style>
.cey46ju5m {
  cx: 12px;
  cy: 9px;
  r: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r1_armb7o {
  d: path("M8.5 17.75h7a.5.5 0 0 0 .5-.5c0-1.9-1.8-3.25-4-3.25s-4 1.35-4 3.25a.5.5 0 0 0 .5.5M3 7.5V5a2 2 0 0 1 2-2h2.5m9 0H19a2 2 0 0 1 2 2v2.5m0 9V19a2 2 0 0 1-2 2h-2.5m-9 0H5a2 2 0 0 1-2-2v-2.5");
}

</style>
