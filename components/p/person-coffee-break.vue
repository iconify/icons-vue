<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v4ug9-byc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-coffee-break" /></template>
<style>
.v4ug9-byc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.872 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5q.811 0 1.567.106M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0m10.534 5.7c-.414-.9 1.116-1.8.216-2.7m-2.75 5.5H20V19a2.5 2.5 0 0 1-2.5 2.5H17a2.5 2.5 0 0 1-2.5-2.5Zm5.5 1a1.5 1.5 0 0 1 0 3");
}

</style>
