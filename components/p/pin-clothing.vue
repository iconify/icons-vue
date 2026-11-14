<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d2_laibuf"/><path class="m5hes0bss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-clothing" /></template>
<style>
.d2_laibuf {
  d: path("M17 12.411V9.5l2 1l2-4L16 3q-4 3.5-8 0L3 6.5l2 4l2-1v11h7.189");
}

.m5hes0bss {
  d: path("m19 22l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
