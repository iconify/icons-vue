<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l9q90oyvl"/><rect class="e0e6a3ddc"/><rect class="bwj0i6b_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:paper-ream" /></template>
<style>
.bwj0i6b_w {
  width: 9.5px;
  height: 5px;
  x: 7.25px;
  y: 12.75px;
  rx: 1px;
}

.e0e6a3ddc {
  width: 18.5px;
  height: 12px;
  x: 2.75px;
  y: 9.25px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l9q90oyvl {
  d: path("M6.75 3.25h10.5m-12.5 3h14.5");
}

</style>
