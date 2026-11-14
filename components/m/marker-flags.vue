<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7ramsbot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:marker-flags" /></template>
<style>
.s7ramsbot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.5v-19m10 19v-10M3.5 3c2.25-1 4.5 1.5 7 .5V9c-2.5 1-4.75-1.5-7-.5m10 3.5c2.25-1 4.5 1.5 7 .5V18c-2.5 1-4.75-1.5-7-.5");
}

</style>
