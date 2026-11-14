<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h_9q0xn8v"/><path class="oncp76bcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:one-on-one" /></template>
<style>
.h_9q0xn8v {
  d: path("M5 3h7.5A2.5 2.5 0 0 1 15 5.5V10a2.5 2.5 0 0 1-2.5 2.5h-5l-3 3v-3a2.5 2.5 0 0 1-2-2.5V5.5A2.5 2.5 0 0 1 5 3Z");
}

.oncp76bcu {
  d: path("M18 9h1a2.5 2.5 0 0 1 2.5 2.5V16a2.5 2.5 0 0 1-2.5 2.5V21l-3-2.5h-4.5A2.5 2.5 0 0 1 9 16v-.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
