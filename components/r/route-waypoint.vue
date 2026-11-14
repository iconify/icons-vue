<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pttl16b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:route-waypoint" /></template>
<style>
.pttl16b9f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 18.5H15a3 3 0 0 0 0-6m-6 0a3.5 3.5 0 0 1 0-7h6.5m-2.439 5.311l.628.628a1.5 1.5 0 0 1 0 2.122l-.628.628a1.5 1.5 0 0 1-2.122 0l-.628-.628a1.5 1.5 0 0 1 0-2.122l.628-.628a1.5 1.5 0 0 1 2.122 0M3.5 18.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m12-13a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
