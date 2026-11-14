<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xre18171o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ticket-volume-chart" /></template>
<style>
.xre18171o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5h9.9m-8.9 0v-4m3 4v-8m3 8V8m3 10.7v-1.9m0-1.9V3.5M15.25 15h6.25v1.75a1 1 0 0 0 0 2v1.75h-6.25v-1.75a1 1 0 0 0 0-2Z");
}

</style>
