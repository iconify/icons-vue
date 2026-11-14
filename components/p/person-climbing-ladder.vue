<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j3z5bfb-p"/><path class="w-2xssboo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:person-climbing-ladder" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j3z5bfb-p {
  d: path("M14.5 2.5v19m5.5-19v19M14.5 7H20m-5.5 5H20m-5.5 5H20M3.75 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

.w-2xssboo {
  d: path("m6.25 7l1.25 7L6 21.5m.75-11.75L14.5 7m-7 7l4-1.5l3 4.5");
}

</style>
