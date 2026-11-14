<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yc47eq77s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:team" /></template>
<style>
.yc47eq77s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5c0-2.9 2.75-5 6.5-5h5c3.75 0 6.5 2.1 6.5 5Zm6.75-16a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-6 6a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m12 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>
