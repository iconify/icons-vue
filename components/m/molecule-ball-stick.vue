<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq-b-iegf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:molecule-ball-stick" /></template>
<style>
.oq-b-iegf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m6.5-7a3 3 0 1 0 6 0a3 3 0 1 0-6 0m6.5 7a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-8-2.25l2.5-2.5m4 0l2.5 2.5");
}

</style>
