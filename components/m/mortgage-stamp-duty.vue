<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o37rbkbdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mortgage-stamp-duty" /></template>
<style>
.o37rbkbdi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 8V5a2 2 0 0 1 4 0v3M6.75 8h10.5A1.75 1.75 0 0 1 19 9.75a1.75 1.75 0 0 1-1.75 1.75H6.75A1.75 1.75 0 0 1 5 9.75A1.75 1.75 0 0 1 6.75 8m-.25 5.75h11m-8.9 4.8l2.5-1.875a1.5 1.5 0 0 1 1.8 0l2.5 1.875a1.5 1.5 0 0 1 .6 1.2v.5a1.25 1.25 0 0 1-1.25 1.25h-5.5A1.25 1.25 0 0 1 8 20.25v-.5a1.5 1.5 0 0 1 .6-1.2");
}

</style>
