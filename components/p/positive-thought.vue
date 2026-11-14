<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u91csjbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:positive-thought" /></template>
<style>
.u91csjbfz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 16.5A3.5 3.5 0 0 1 5.5 10A4.5 4.5 0 0 1 12 4.5a4.5 4.5 0 0 1 7.5 4a4.25 4.25 0 0 1-2 8ZM3.75 20a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0M12.5 8v5M10 10.5h5");
}

</style>
