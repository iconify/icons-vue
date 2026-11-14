<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itfu4nbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rice-cakes" /></template>
<style>
.itfu4nbke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 16h10a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5h-10A2.5 2.5 0 0 1 3 18.5A2.5 2.5 0 0 1 5.5 16m3-5h10a2.5 2.5 0 0 1 2.5 2.5a2.5 2.5 0 0 1-2.5 2.5h-10A2.5 2.5 0 0 1 6 13.5A2.5 2.5 0 0 1 8.5 11M4 7.25a8 3.5 0 1 0 16 0a8 3.5 0 1 0-16 0m4.5 0h.01m3.49 0h.01m3.49 0h.01");
}

</style>
