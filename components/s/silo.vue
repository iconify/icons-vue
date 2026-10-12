<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hepvlhbce"/><rect class="ehe7x7b7h"/><path class="hvw5t0tyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:silo" /></template>
<style>
.ehe7x7b7h {
  width: 7.25px;
  height: 13.5px;
  x: 3px;
  y: 7.75px;
  rx: 0.75px;
}

.hepvlhbce {
  d: path("M3.3 7.35L6.33 3.4q.3-.4.6 0l3.02 3.95q.3.4-.2.4H3.5q-.5 0-.2-.4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hvw5t0tyu {
  d: path("M3 11.75h7.25m-7.25 4h7.25m3.5 5.5V12a3.75 3.25 0 0 1 7.5 0v9.25Zm0-5.5h7.5m-11-5.5l3.5 2.25");
}

</style>
