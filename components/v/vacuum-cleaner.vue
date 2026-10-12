<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="or24ppmex"/><rect class="y_piwpb6h"/><path class="i7dw9jbwd"/><circle class="svx1ycb0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vacuum-cleaner" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i7dw9jbwd {
  d: path("M8.88 5.5C12.5 5.5 14 8 14 12.25m-.75 0h4.5a3.5 3.5 0 0 1 3.5 3.5v2a3.5 3.5 0 0 1-3.5 3.5h-4.5a1.5 1.5 0 0 1-1.5-1.5v-6a1.5 1.5 0 0 1 1.5-1.5");
}

.or24ppmex {
  d: path("M9.5 2.75L6 18.25");
}

.svx1ycb0c {
  cx: 16.5px;
  cy: 16.75px;
  r: 2px;
}

.y_piwpb6h {
  width: 7px;
  height: 3px;
  x: 2.75px;
  y: 18.25px;
  rx: 1.5px;
}

</style>
