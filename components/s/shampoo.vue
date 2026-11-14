<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr_qh4bmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shampoo" /></template>
<style>
.vr_qh4bmp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.875 9.5h2.25a4.375 4.375 0 0 1 4.375 4.375v2.75A4.375 4.375 0 0 1 13.125 21h-2.25A4.375 4.375 0 0 1 6.5 16.625v-2.75A4.375 4.375 0 0 1 10.875 9.5m.625-3h1A1.5 1.5 0 0 1 14 8a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 10 8a1.5 1.5 0 0 1 1.5-1.5m.5 0v-3h4.5M9.5 14h5m-5 3h3");
}

</style>
