<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="mztew9b7r"/><path class="i8lkjhbol"/><circle class="bc1vn5bja"/><path class="zg2x11b5s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:packing-station" /></template>
<style>
.bc1vn5bja {
  cx: 18.25px;
  cy: 8.75px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i8lkjhbol {
  d: path("M9.75 5v2.5");
}

.mztew9b7r {
  width: 8.5px;
  height: 5.75px;
  x: 5.5px;
  y: 5px;
  rx: 1px;
}

.zg2x11b5s {
  d: path("M2.75 13.25h18.5m-16.5 0v8m14.5-8v8m-14.5-3.5h14.5");
}

</style>
