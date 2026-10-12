<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="w1ghlpbud"/><path class="nzn5dcbmz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:page-number" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nzn5dcbmz {
  d: path("M7.5 7h9m-9 3.5h9m-5.5 5l1.5-1.25v4.5");
}

.w1ghlpbud {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
