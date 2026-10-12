<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0wnaopfd"/><circle class="n81udiknj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reminder-bell" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n81udiknj {
  cx: 19px;
  cy: 4.5px;
  r: 1.5px;
}

.r0wnaopfd {
  d: path("M10.5 4.5a5 5 0 0 0-5 5v3.25l-1.5 3h13l-1.5-3V9.5a5 5 0 0 0-5-5m-2 14.25a2 2 0 0 0 4 0");
}

</style>
