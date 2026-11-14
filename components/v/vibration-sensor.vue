<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6-13dbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vibration-sensor" /></template>
<style>
.l6-13dbco {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 7.5h2a3.5 3.5 0 0 1 3.5 3.5v2a3.5 3.5 0 0 1-3.5 3.5h-2A3.5 3.5 0 0 1 7.5 13v-2A3.5 3.5 0 0 1 11 7.5m1 4.5h.01M4.5 7.5L3 9.75L4.5 12L3 14.25l1.5 2.25m15-9L21 9.75L19.5 12l1.5 2.25l-1.5 2.25");
}

</style>
