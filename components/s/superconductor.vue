<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d20vcjb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:superconductor" /></template>
<style>
.d20vcjb2s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 13.5v-5a6.5 6.5 0 0 1 13 0v5h-4v-5a2.5 2.5 0 0 0-5 0v5ZM5.25 17h13.5a1.75 1.75 0 0 1 1.75 1.75v1a1.75 1.75 0 0 1-1.75 1.75H5.25a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 5.25 17m.25-6h4m5 0h4");
}

</style>
