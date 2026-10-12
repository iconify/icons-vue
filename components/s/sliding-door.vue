<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="w1ghlpbud"/><path class="zqmhoxb5y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sliding-door" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w1ghlpbud {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 2px;
}

.zqmhoxb5y {
  d: path("M12 2.75v18.5M9.25 10.5v3M14.5 12H18m-1.5-1.5L18 12l-1.5 1.5");
}

</style>
