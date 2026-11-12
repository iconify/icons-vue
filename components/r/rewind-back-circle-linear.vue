<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hdz8l5g_x"/><path class="u836v1b4v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-back-circle-linear" /></template>
<style>
.hdz8l5g_x {
  d: path("M2 12C2 17.5228 6.47715 22 12 22C17.5228 22 22 17.5228 22 12C22 6.47715 17.5228 2 12 2C6.47715 2 2 6.47715 2 12Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u836v1b4v {
  d: path("M11.0005 8.07141L7.77893 10.3725C6.66223 11.1702 6.66223 12.8298 7.77893 13.6274L11.0005 15.9286M16.5005 15.0568V8.94317C16.5005 8.1298 15.5811 7.65667 14.9192 8.12944L10.6397 11.1862C10.0814 11.5851 10.0814 12.4149 10.6397 12.8137L14.9192 15.8705C15.5811 16.3433 16.5005 15.8702 16.5005 15.0568Z");
}

</style>
