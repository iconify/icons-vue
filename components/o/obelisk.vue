<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ksx76rt8b"/><rect class="og2ro6o3n"/><path class="o9z8ycbge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:obelisk" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ksx76rt8b {
  d: path("m12.27 3.17l1.21 1.91q.27.42.31.92l.92 12q.04.5-.46.5h-4.5q-.5 0-.46-.5l.92-12q.04-.5.31-.92l1.21-1.91q.27-.42.54 0");
}

.o9z8ycbge {
  d: path("M10.25 5.5h3.5");
}

.og2ro6o3n {
  width: 10.5px;
  height: 2.75px;
  x: 6.75px;
  y: 18.5px;
  rx: 0.75px;
}

</style>
