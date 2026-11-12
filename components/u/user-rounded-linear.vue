<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="dtl23o_xq"/><ellipse class="srendccfk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-rounded-linear" /></template>
<style>
.dtl23o_xq {
  cx: 12px;
  cy: 6px;
  r: 4px;
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.srendccfk {
  cx: 12px;
  cy: 17px;
  rx: 7px;
  ry: 4px;
}

</style>
