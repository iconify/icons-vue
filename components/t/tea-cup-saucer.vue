<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gib53jbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tea-cup-saucer" /></template>
<style>
.gib53jbic {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 9h12v4c0 2.5-2 4-6 4s-6-1.5-6-4Zm12 1c3.5 0 3.5 4.5 0 4.5m-13 6h14");
}

</style>
