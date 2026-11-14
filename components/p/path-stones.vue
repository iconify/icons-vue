<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m0v11mb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:path-stones" /></template>
<style>
.m0v11mb9e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 18.5a4.5 2.75 0 1 0 9 0a4.5 2.75 0 1 0-9 0M12.5 12a3.75 2.25 0 1 0 7.5 0a3.75 2.25 0 1 0-7.5 0M7.25 5.5a3 2 0 1 0 6 0a3 2 0 1 0-6 0");
}

</style>
