<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nph-4y1xm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:smash-shot" /></template>
<style>
.nph-4y1xm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8.5a5 6 0 1 0 10 0a5 6 0 1 0-10 0m5 6v7m-5-13h10m-5-6v12m5.5 4a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3-11v5");
}

</style>
