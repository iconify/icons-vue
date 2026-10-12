<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hoi44xq4a"/><path class="bl9no13pu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:site-plan" /></template>
<style>
.bl9no13pu {
  d: path("M7.75 6.5h5.5q.75 0 .75.75v2.5q0 .75-.75.75h-1.5q-.75 0-.75.75v2.5q0 .75-.75.75h-2.5q-.75 0-.75-.75v-6.5q0-.75.75-.75m9.75 12V14m-1.25 1.25L17.5 14l1.25 1.25M2.75 18h11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hoi44xq4a {
  width: 18.5px;
  height: 18.5px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
