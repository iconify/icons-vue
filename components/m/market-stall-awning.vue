<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js4kvlbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:market-stall-awning" /></template>
<style>
.js4kvlbqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 6.5L4.5 3h15L21 6.5m-18 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0a2.25 2.25 0 0 0 4.5 0M5 8.75V21M19 8.75V21M3.5 16h17m-11-3.5h.5a1.5 1.5 0 0 1 1.5 1.5v.5A1.5 1.5 0 0 1 10 16h-.5A1.5 1.5 0 0 1 8 14.5V14a1.5 1.5 0 0 1 1.5-1.5m4.5 0h.5A1.5 1.5 0 0 1 16 14v.5a1.5 1.5 0 0 1-1.5 1.5H14a1.5 1.5 0 0 1-1.5-1.5V14a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
