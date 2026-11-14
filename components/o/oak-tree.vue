<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p339yybbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:oak-tree" /></template>
<style>
.p339yybbh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 15a3 3 0 0 1-2-5.5A3.5 3.5 0 0 1 8.5 5a4 4 0 0 1 7 0A3.5 3.5 0 0 1 20 9.5a3 3 0 0 1-2 5.5Zm4.5 0l-.5 6.5m3.5-6.5l.5 6.5");
}

</style>
