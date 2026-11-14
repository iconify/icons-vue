<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td7dwhb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shaving-brush" /></template>
<style>
.td7dwhb6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 12C6 9 7.5 3.5 12 3.5S18 9 16.5 12Zm3.25 0h2.5a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25h-2.5a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 10.75 12m.5 2.5h1.5A3.25 3.25 0 0 1 16 17.75A3.25 3.25 0 0 1 12.75 21h-1.5A3.25 3.25 0 0 1 8 17.75a3.25 3.25 0 0 1 3.25-3.25");
}

</style>
