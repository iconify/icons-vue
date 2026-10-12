<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qw-6d-blf"/><rect class="tj8-vzb-s"/><path class="p2lid9b9e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:presentation-screen" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p2lid9b9e {
  d: path("M8.5 13.25v-2m3.5 2v-4.5m3.5 4.5v-3.5m-3.5 7v4.5m0-4.5l-3.5 4.5m3.5-4.5l3.5 4.5");
}

.qw-6d-blf {
  d: path("M2.75 3.25h18.5");
}

.tj8-vzb-s {
  width: 15.5px;
  height: 10.75px;
  x: 4.25px;
  y: 6px;
  rx: 1.5px;
}

</style>
