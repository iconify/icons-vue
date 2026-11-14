<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvgfb08-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:unbalanced-forces" /></template>
<style>
.tvgfb08-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 9.5h1A1.75 1.75 0 0 1 12 11.25v1.5a1.75 1.75 0 0 1-1.75 1.75h-1a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 9.25 9.5M12 12h9.5M17 7.5l4.5 4.5l-4.5 4.5M7.5 12h-5m2.25-2.25L2.5 12l2.25 2.25");
}

</style>
