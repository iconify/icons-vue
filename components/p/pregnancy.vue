<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="pmpn_x9is"/><path class="id9tjvb1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pregnancy" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.id9tjvb1o {
  d: path("M8.75 8.75C7.5 10.75 7 13.5 7.5 16.5l.5 4.75m3.5-12.5c.25 1.25.5 2.25 1 2.75m0 0C16 12 18 14 18 16.25S15.25 20 11.75 20v1.25");
}

.pmpn_x9is {
  cx: 10px;
  cy: 5.5px;
  r: 2.25px;
}

</style>
