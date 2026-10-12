<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffpyybczd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wide-angle-lens" /></template>
<style>
.ffpyybczd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 8h4.5a2 2 0 0 1 2 2v.25h1.5a1 1 0 0 1 1 1v1.5a1 1 0 0 1-1 1h-1.5V14a2 2 0 0 1-2 2h-4.5a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2m11.57.94l4.93-5.88m-4.93 12l4.93 5.88");
}

</style>
