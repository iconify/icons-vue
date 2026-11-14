<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz4vwfb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:networking-event" /></template>
<style>
.cz4vwfb6m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 8.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm11 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-12.5 10c0-3 2-4.5 4-4.5s4 1.5 4 4.5m3 0c0-3 2-4.5 4-4.5s4 1.5 4 4.5M9 8.5h6");
}

</style>
