<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="arjr-ccnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:share-lock" /></template>
<style>
.arjr-ccnd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 5.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m-11 6.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0M9 10.5L15 7m-6 6.5l4.5 2.75m3.25.25h2.5A1.75 1.75 0 0 1 21 18.25v1A1.75 1.75 0 0 1 19.25 21h-2.5A1.75 1.75 0 0 1 15 19.25v-1a1.75 1.75 0 0 1 1.75-1.75m-.5 0v-1.25a1.75 1.75 0 0 1 3.5 0v1.25");
}

</style>
