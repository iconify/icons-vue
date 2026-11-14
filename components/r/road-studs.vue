<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq906ubxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:road-studs" /></template>
<style>
.dq906ubxz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5L9 2.5m12.5 19L15 2.5M9.75 18a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m.5-6.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m.5-6a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

</style>
