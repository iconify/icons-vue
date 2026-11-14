<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o_36gc11s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-lab" /></template>
<style>
.o_36gc11s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 3v5.5l-5 10C4 19.75 4.75 21 6 21h12c1.25 0 2-1.25 1.5-2.5l-5-10V3M8 3h8M6.75 14h10.5");
}

</style>
