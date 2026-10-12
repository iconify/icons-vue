<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="an9l3ju_g"/><path class="bs8ao7ncv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tree-planting" /></template>
<style>
.an9l3ju_g {
  cx: 9.5px;
  cy: 8px;
  r: 5.25px;
}

.bs8ao7ncv {
  d: path("M9.5 13.25v5m-6.5 3c1-2.25 3.5-3 6.5-3s5.5.75 6.5 3Zm15.5-18V13m-1.75 0h3.5v2.75a1.75 1.75 0 0 1-3.5 0Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
