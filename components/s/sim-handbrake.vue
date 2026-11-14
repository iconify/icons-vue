<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sy2826n6h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sim-handbrake" /></template>
<style>
.sy2826n6h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.5h17M6 21.5v-3a4 4 0 0 1 8 0v3m-4-7l3.5-5.25M17 3.219za1.75 1.75 0 0 1 .641 2.39l-1.75 3.032a1.75 1.75 0 0 1-2.391.64a1.75 1.75 0 0 1-.641-2.39l1.75-3.032A1.75 1.75 0 0 1 17 3.219");
}

</style>
