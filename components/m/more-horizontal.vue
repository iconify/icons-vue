<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="zf18uhbyq"/><circle class="lf940mbnz"/><circle class="n0_s6y1ca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:more-horizontal" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lf940mbnz {
  cx: 12px;
  cy: 12px;
  r: 1.25px;
}

.n0_s6y1ca {
  cx: 19.25px;
  cy: 12px;
  r: 1.25px;
}

.zf18uhbyq {
  cx: 4.75px;
  cy: 12px;
  r: 1.25px;
}

</style>
