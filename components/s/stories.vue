<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="d8mt2_n-r"/><circle class="ybj6vw61j"/><path class="lbks89bsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stories" /></template>
<style>
.d8mt2_n-r {
  cx: 12px;
  cy: 12px;
  r: 6.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lbks89bsr {
  d: path("M9.25 15.25a2.75 2.75 0 0 1 5.5 0M13.61 2.89a9.25 9.25 0 0 1 5.48 3.16m1.6 2.79a9.25 9.25 0 0 1 0 6.32m-1.6 2.79a9.25 9.25 0 0 1-5.48 3.16m-3.22 0a9.25 9.25 0 0 1-5.48-3.16m-1.6-2.79a9.25 9.25 0 0 1 0-6.32m1.6-2.79a9.25 9.25 0 0 1 5.48-3.16");
}

.ybj6vw61j {
  cx: 12px;
  cy: 10.5px;
  r: 1.9px;
}

</style>
