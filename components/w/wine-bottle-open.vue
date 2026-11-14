<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5hr7ccxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wine-bottle-open" /></template>
<style>
.h5hr7ccxd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.5h3V7q2.5 2 2.5 5v8q0 1.5-1.5 1.5H6q-1.5 0-1.5-1.5v-8q0-3 2.5-5Zm9.628 13.192l2.265-1.056a1.75 1.75 0 0 1 2.326.846a1.75 1.75 0 0 1-.847 2.326l-2.265 1.056a1.75 1.75 0 0 1-2.326-.846a1.75 1.75 0 0 1 .847-2.326M4.5 14.5h8");
}

</style>
