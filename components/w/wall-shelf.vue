<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="w1ghlpbud"/><path class="vc1_wqb-u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wall-shelf" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vc1_wqb-u {
  d: path("M3.75 12h16.5m-13-6v3.25M9.75 6v3.25m2.75-3l1.75 3m-7 6v3m8.5-3v3");
}

.w1ghlpbud {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
