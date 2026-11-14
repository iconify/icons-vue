<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ra4h4dbnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:meet-the-team" /></template>
<style>
.ra4h4dbnm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m-3 12.5c0-3.5 3-6 6.5-6c1.051 0 2.056.225 2.949.635M16 4.5a3.5 3.5 0 0 1 .906 6.881M16.25 15h3.5a1.75 1.75 0 0 1 1.75 1.75v3a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75v-3A1.75 1.75 0 0 1 16.25 15m-1.75 2.5h7");
}

</style>
