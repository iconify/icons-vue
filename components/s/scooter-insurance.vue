<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmtqa-byh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scooter-insurance" /></template>
<style>
.hmtqa-byh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 18a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm13 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm-8.5 0h8.5m2.25 0l-2-14M14 4h5M5.75 3L8.5 4v2c0 1.6-1.1 2.5-2.75 3.25C4.1 8.5 3 7.6 3 6V4Z");
}

</style>
