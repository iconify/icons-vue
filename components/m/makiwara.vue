<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="un2zl1bmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:makiwara" /></template>
<style>
.un2zl1bmz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 5V2.5h4V5m-3.875 0h3.75A2.625 2.625 0 0 1 16.5 7.625v1.25a2.625 2.625 0 0 1-2.625 2.625h-3.75A2.625 2.625 0 0 1 7.5 8.875v-1.25A2.625 2.625 0 0 1 10.125 5M10 11.5V21m4-9.5V21m-9.5 0h15");
}

</style>
