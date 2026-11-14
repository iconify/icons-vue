<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4pfy-bre"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:particle" /></template>
<style>
.w4pfy-bre {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 9a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0M4 20l5.75-5.75M4.5 15.5l3-3m1 7l3-3");
}

</style>
