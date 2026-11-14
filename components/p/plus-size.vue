<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m42z1r2tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plus-size" /></template>
<style>
.m42z1r2tm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5L7 6l1.25 3L4 20.5q6 1.5 12 0L11.75 9L13 6l-.5-3.5m6.25 0V8M16 5.25h5.5");
}

</style>
