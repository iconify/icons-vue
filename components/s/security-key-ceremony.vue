<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2-q8_6th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:security-key-ceremony" /></template>
<style>
.g2-q8_6th {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm9 0h10m-3 0v3m3-3V17m-18-9V3.5l1.75 1.75L7 2.5l1.75 2.75L10.5 3.5V8Z");
}

</style>
