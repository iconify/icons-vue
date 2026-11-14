<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z4ynztbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pen-tool" /></template>
<style>
.z4ynztbwj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 17c1.5-6.5 12.5-6.5 14 0M4.5 17h1A1.5 1.5 0 0 1 7 18.5v1A1.5 1.5 0 0 1 5.5 21h-1A1.5 1.5 0 0 1 3 19.5v-1A1.5 1.5 0 0 1 4.5 17m14 0h1a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5v-1a1.5 1.5 0 0 1 1.5-1.5M4 6h5.5m5 0H20m-9-2h2a1.5 1.5 0 0 1 1.5 1.5v1A1.5 1.5 0 0 1 13 8h-2a1.5 1.5 0 0 1-1.5-1.5v-1A1.5 1.5 0 0 1 11 4");
}

</style>
