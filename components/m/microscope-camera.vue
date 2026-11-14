<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a--fwsbda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:microscope-camera" /></template>
<style>
.a--fwsbda {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.688 2.5h5.125A2.19 2.19 0 0 1 14 4.688v.625A2.19 2.19 0 0 1 11.813 7.5H6.688A2.19 2.19 0 0 1 4.5 5.313v-.625A2.19 2.19 0 0 1 6.688 2.5m2.062 5h1a1.75 1.75 0 0 1 1.75 1.75v3A1.75 1.75 0 0 1 9.75 14h-1A1.75 1.75 0 0 1 7 12.25v-3A1.75 1.75 0 0 1 8.75 7.5m2.75 3c5 0 7 4.5 4 7.5v2.5M5 17h7.5M5 20.5h14");
}

</style>
