<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j54zmkbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pixel-gem" /></template>
<style>
.j54zmkbba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 4.5h8.5V7h2.5v2.5h2.5V12h-2.5v2.5h-2.5V17h-3v2.5h-2.5V17h-3v-2.5h-2.5V12h-2.5V9.5h2.5V7h2.5Zm-5 5h18.5");
}

</style>
