<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zoayk9bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:workout-library" /></template>
<style>
.zoayk9bgm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 4.5C8.75 3 5.75 2.75 2.5 3.5V14c3.25-.75 6.25-.5 8.5 1c2.25-1.5 5.25-1.75 8.5-1V3.5c-3.25-.75-6.25-.5-8.5 1m0 0V15m4 2za1.25 1.25 0 0 1 1.25 1.25v2A1.25 1.25 0 0 1 15 21.5a1.25 1.25 0 0 1-1.25-1.25v-2A1.25 1.25 0 0 1 15 17m5.5 0za1.25 1.25 0 0 1 1.25 1.25v2a1.25 1.25 0 0 1-1.25 1.25a1.25 1.25 0 0 1-1.25-1.25v-2A1.25 1.25 0 0 1 20.5 17m-4.25 2.25h3");
}

</style>
