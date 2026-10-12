<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an9_a8ejw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:waterspout" /></template>
<style>
.an9_a8ejw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 9.25H9c.6 3.25 1.9 6 3 7.75c1.1-1.75 2.4-4.5 3-7.75h2.75a2.5 2.5 0 1 0-2.43-3.1a3.5 3.5 0 0 0-6.64 0a2.5 2.5 0 1 0-2.43 3.1M4 20.25q2-1.5 4 0t4 0t4 0t4 0");
}

</style>
