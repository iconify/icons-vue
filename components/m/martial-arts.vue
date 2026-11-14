<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx__k964g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:martial-arts" /></template>
<style>
.qx__k964g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 4.5h1.5a1.75 1.75 0 0 1 1.75 1.75v3.5a1.75 1.75 0 0 1-1.75 1.75h-1.5A1.75 1.75 0 0 1 9.5 9.75v-3.5a1.75 1.75 0 0 1 1.75-1.75M9.5 5.75c-3 0-5-.25-7-1.25m0 3.75c2 1 4 1 7 1m5-3.5c3 0 5-.25 7-1.25m0 3.75c-2 1-4 1-7 1m-4 2.25l-3 8h3.25l1-8m.5 0l1 8h3.25l-3-8");
}

</style>
