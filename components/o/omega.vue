<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i76jp6-5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:omega" /></template>
<style>
.i76jp6-5p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 20H9v-2c-2.5-1.25-4.25-3.6-4.25-6.5C4.75 7.3 8 4.25 12 4.25s7.25 3.05 7.25 7.25c0 2.9-1.75 5.25-4.25 6.5v2h4.5");
}

</style>
