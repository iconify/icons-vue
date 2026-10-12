<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="yij3ylb0l"/><rect class="yijh0rbhp"/><path class="jgg8vcckw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shopping-trolley-bag" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jgg8vcckw {
  d: path("M4.25 13h15.5a1 1 0 0 1 .97 1.24l-1.25 5.1a2.5 2.5 0 0 1-2.43 1.91H6.96a2.5 2.5 0 0 1-2.43-1.91l-1.25-5.1A1 1 0 0 1 4.25 13M9 15.25v3m3-3v3m3-3v3");
}

.yij3ylb0l {
  cx: 8px;
  cy: 7.25px;
  r: 2.75px;
}

.yijh0rbhp {
  width: 3.5px;
  height: 7.25px;
  x: 13.25px;
  y: 2.75px;
  rx: 1.5px;
}

</style>
