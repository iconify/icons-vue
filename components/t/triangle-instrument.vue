<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h86de_a4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:triangle-instrument" /></template>
<style>
.h86de_a4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.9 6.6L3.5 19a1.5 1.5 0 0 0 1.3 2.25h14.4A1.5 1.5 0 0 0 20.5 19L13.1 6.6a1.25 1.25 0 0 0-1.6-.5m.5-3.35v2.9m9.25 4.85l-6 5");
}

</style>
