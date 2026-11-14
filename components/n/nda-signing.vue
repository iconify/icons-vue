<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-9h6pbpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nda-signing" /></template>
<style>
.f-9h6pbpd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 9h2.25a2.625 2.625 0 0 1 2.625 2.625v1.25A2.625 2.625 0 0 1 7.875 15.5h-2.25A2.625 2.625 0 0 1 3 12.875v-1.25A2.625 2.625 0 0 1 5.625 9M4.75 9V7a2 2 0 0 1 4 0v2M20 9.304za1.5 1.5 0 0 1 .549 2.049l-3.684 6.38a1.5 1.5 0 0 1-.517.531l-1.011.616a.854.854 0 0 1-1.299-.75l.029-1.183a1.5 1.5 0 0 1 .2-.714l3.684-6.38A1.5 1.5 0 0 1 20 9.304M3 19.75h11");
}

</style>
