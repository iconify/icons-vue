<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d32a-65sz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:phishing-warning" /></template>
<style>
.d32a-65sz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 6.25v9.25a4.25 4.25 0 0 1-8.5 0V13m0 0l2.25 2.25M10.5 4a2 2 0 1 0 4 0a2 2 0 1 0-4 0M18 14.75v3.5M18 21h.01");
}

</style>
