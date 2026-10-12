<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hrhyb1bxi"/><circle class="qhvrk_ymv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toggle-off" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hrhyb1bxi {
  width: 18.5px;
  height: 11px;
  x: 2.75px;
  y: 6.5px;
  rx: 5.5px;
}

.qhvrk_ymv {
  cx: 8.25px;
  cy: 12px;
  r: 3px;
}

</style>
