<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbaa-hb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tip-jar" /></template>
<style>
.lbaa-hb5p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 6.5h11A1.5 1.5 0 0 1 19 8a1.5 1.5 0 0 1-1.5 1.5h-11A1.5 1.5 0 0 1 5 8a1.5 1.5 0 0 1 1.5-1.5m0 3C4.75 12 4.75 21 8.5 21h7c3.75 0 3.75-9 2-11.5M9 6.5l1-4h5l-.5 4");
}

</style>
