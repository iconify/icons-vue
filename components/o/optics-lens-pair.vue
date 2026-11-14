<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gukz14bhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:optics-lens-pair" /></template>
<style>
.gukz14bhd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 12a2 7 0 1 0 4 0a2 7 0 1 0-4 0m8 0a2 7 0 1 0 4 0a2 7 0 1 0-4 0M2.5 12h19");
}

</style>
