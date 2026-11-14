<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y28mi8bnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:suppository" /></template>
<style>
.y28mi8bnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 16L11 8c3.25-3 6-3.75 7.25-2.25C19.75 7 19 9.75 16 13l-8 7.75Zm2-2.25l5 5");
}

</style>
