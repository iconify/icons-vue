<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="u4_9fcb4o"/><path class="scrh66bra"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tv-smart" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.scrh66bra {
  d: path("m7 17.25l-1.25 4m11.25-4l1.25 4m-7.75-13v4.5l3.75-2.25Z");
}

.u4_9fcb4o {
  width: 18.5px;
  height: 13.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
}

</style>
