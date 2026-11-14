<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpcmfrdan"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:missing-values" /></template>
<style>
.bpcmfrdan {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8H4a2 2 0 0 0-2 2v4a2 2 0 0 0 2 2h8m5-8h3a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-3Zm-5 0v8M7 8v8m6.75-8h1.5m-1.5 8h1.5M4.5 12h.01m4.99 0h.01m9.99 0h.01");
}

</style>
