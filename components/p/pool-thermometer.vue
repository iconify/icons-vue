<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1ek3gzwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pool-thermometer" /></template>
<style>
.n1ek3gzwp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4.5a2 2 0 0 1 4 0v8.25a3.25 3.25 0 1 1-4 0ZM12 8v7m-9.5 0q1.75-1.5 3.5 0q.75.75 1.5.5m9 0q.75.25 1.5-.5q1.75-1.5 3.5 0");
}

</style>
