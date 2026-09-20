<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op5rf9vmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:travel-pillow-outline-regular" /></template>
<style>
.op5rf9vmb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 10a8 8 0 1 0 16 0 4 4 0 0 1 -4 0 4 4 0 0 0 -8 0 4 4 0 0 1 -4 0");
}

</style>
