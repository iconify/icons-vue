<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1tldspqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:soccer-stud-key" /></template>
<style>
.q1tldspqp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 4h10M8 4v11m-.651 0h1.302a1.5 1.5 0 0 1 1.286.728l.6 1a1.5 1.5 0 0 1 0 1.544l-.6 1A1.5 1.5 0 0 1 8.651 20H7.349a1.5 1.5 0 0 1-1.286-.728l-.6-1a1.5 1.5 0 0 1 0-1.544l.6-1A1.5 1.5 0 0 1 7.349 15m7.151-2h6L19 17h-3Zm3 4v3.5");
}

</style>
