<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mr-9pysac"/><rect class="i12np7brb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:senate-chamber" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i12np7brb {
  width: 4px;
  height: 5px;
  x: 10px;
  y: 16.25px;
  rx: 1px;
}

.mr-9pysac {
  d: path("M3 16.25a9 9 0 0 1 1.24-4.55m.61-.92A9 9 0 0 1 8.6 7.92m1.04-.36a9 9 0 0 1 4.72 0m1.04.36a9 9 0 0 1 3.75 2.86m.61.92A9 9 0 0 1 21 16.25m-14.5 0a5.5 5.5 0 0 1 2.22-4.41m.81-.5a5.5 5.5 0 0 1 4.94 0m.81.5a5.5 5.5 0 0 1 2.22 4.41");
}

</style>
