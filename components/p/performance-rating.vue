<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjvezib9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:performance-rating" /></template>
<style>
.hjvezib9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m4.25 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m4.25 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m4.25 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M19 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M3.5 12h.01m4.24 0h.01M12 12h.01");
}

</style>
