<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="autxr5-my"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spectrograph-astro" /></template>
<style>
.autxr5-my {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11 5l6.5 14h-13Zm-8.5 9l5.25-2m6.5 0l7.25-3.5M14.25 12l7.25.5m-7.25-.5l7.25 4.5");
}

</style>
