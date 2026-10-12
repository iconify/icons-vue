<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ra-u47bfz"/><rect class="s25l42syc"/><path class="klb7v-6wr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:roadside-stall" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.klb7v-6wr {
  d: path("M3.75 15.5h16.5");
}

.ra-u47bfz {
  d: path("M5 3.25h14l2.25 4v.5a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0a2.25 2.25 0 0 1-4.5 0v-.5Zm0 7v2.25m14-2.25v2.25");
}

.s25l42syc {
  width: 16.5px;
  height: 8.75px;
  x: 3.75px;
  y: 12.5px;
  rx: 1.25px;
}

</style>
