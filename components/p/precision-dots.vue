<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-ngokhtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:precision-dots" /></template>
<style>
.u-ngokhtw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 4h.01M12 4h.01M20 4h.01M4 12h.01M20 12h.01M4 20h.01M12 20h.01M20 20h.01M12 8.5v7M8.5 12h7");
}

</style>
