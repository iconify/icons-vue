<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mcdrmjbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:masks-theater-round" /></template>
<style>
.mcdrmjbyr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m11.076 11.668l-.695-3.939a3 3 0 0 1 2.434-3.475l3.94-.695a3 3 0 0 1 3.474 2.434l.695 3.939a5 5 0 0 1-9.848 1.736m1.495 6.36a5.002 5.002 0 0 1-9.495-2.896l.695-3.94A3 3 0 0 1 7.246 8.76l.28.05m5.81-1.6h.01m3.929-.696h.01m-3.428 3.65a2.267 2.267 0 0 0 3.939-.695M6.725 11.713h.01m-.705 3.94a2.267 2.267 0 0 1 3.94.694");
}

</style>
