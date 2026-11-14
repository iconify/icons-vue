<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhgwf20qq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:retirement-savings" /></template>
<style>
.nhgwf20qq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 11c0-3.25 3-5.5 7-5.5c3 0 5.5 1.25 6.5 3.5H20v4.5h-1.5c-.5 1.5-1.5 2.5-3 3.25v2.75H13v-2h-3v2H7.5v-3C6 15.5 5 13.5 5 11m0-1L3 8.5m7 0h3m2.5 2.25h.01");
}

</style>
