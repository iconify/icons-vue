<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnki-9-3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pest-neem-oil" /></template>
<style>
.pnki-9-3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 10.5h2.5A3.5 3.5 0 0 1 14 14v3.5a3.5 3.5 0 0 1-3.5 3.5H8a3.5 3.5 0 0 1-3.5-3.5V14A3.5 3.5 0 0 1 8 10.5m-1.5 0V4h7L16 6v1.5h-4.5v3M19 3.75h.01m-.01 3h.01m-.01 3h.01");
}

</style>
