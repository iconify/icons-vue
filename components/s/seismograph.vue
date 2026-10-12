<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="nh6gitbrz"/><path class="dvzhdg8hu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:seismograph" /></template>
<style>
.dvzhdg8hu {
  d: path("M2.75 12h3L8 8.5l3 7l3-7l2.25 3.5h4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nh6gitbrz {
  width: 16.5px;
  height: 14.5px;
  x: 3.75px;
  y: 4.75px;
  rx: 2.5px;
}

</style>
