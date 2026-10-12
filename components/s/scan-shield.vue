<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppi88gbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:scan-shield" /></template>
<style>
.ppi88gbov {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.5V5A2.25 2.25 0 0 1 5 2.75h2.5m9 0H19A2.25 2.25 0 0 1 21.25 5v2.5m0 9V19A2.25 2.25 0 0 1 19 21.25h-2.5m-9 0H5A2.25 2.25 0 0 1 2.75 19v-2.5M12 6.5l4.5 1.6v3.65c0 2.9-1.85 5-4.5 6.25c-2.65-1.25-4.5-3.35-4.5-6.25V8.1ZM4.25 12h15.5");
}

</style>
