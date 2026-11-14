<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi_7teb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:seasonal-hire" /></template>
<style>
.mi_7teb5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0M4 21c0-3.823 3.197-6.276 7.409-6.485M15.5 17.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2-4.5v1.25m0 6.5V22M13 17.5h1.25m6.5 0H22m-7.75-3.25l1 1m5.5-1l-1 1m-5.5 5.5l1-1m5.5 1l-1-1");
}

</style>
