<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="y-zrt3b2q"/><path class="lonci-b-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:whiteboard" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lonci-b-z {
  d: path("M6.5 7h7m-7 3.5h4m4.75 1.5l2.5-2.5M8 15.75l-2 5.5m10-5.5l2 5.5m-6-5.5v5.5");
}

.y-zrt3b2q {
  width: 18.5px;
  height: 13px;
  x: 2.75px;
  y: 2.75px;
  rx: 2px;
}

</style>
