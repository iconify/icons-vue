<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpd6u38_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:resonance" /></template>
<style>
.bpd6u38_z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 12q1.25-1.5 2.5 0q1.25 3 2.5 0q1.25-5 2.5 0q1.25 7 2.5 0q1.25-9 2.5 0M2.75 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
