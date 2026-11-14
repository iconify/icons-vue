<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pz3rx5bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:snow-gauge" /></template>
<style>
.pz3rx5bfs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 2.5L7 7v13a1.5 1.5 0 0 0 1.5 1.5h2A1.5 1.5 0 0 0 12 20V7l3.5-4.5M7 13h2.25m9.25 2.5v6M15.75 17l5.5 3m-5.5 0l5.5-3");
}

</style>
