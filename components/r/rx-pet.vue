<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm4i71bsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rx-pet" /></template>
<style>
.cm4i71bsd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 12c3.5 0 6.5 4 6.5 6.5c0 2-1.75 2.5-3.5 2s-4.25-.5-6 0s-3.5 0-3.5-2c0-2.5 3-6.5 6.5-6.5Zm-9.75-.5a1.75 2.25 0 1 0 3.5 0a1.75 2.25 0 1 0-3.5 0Zm4.25-6a2 2.75 0 1 0 4 0a2 2.75 0 1 0-4 0Zm7 0a2 2.75 0 1 0 4 0a2 2.75 0 1 0-4 0Zm4.75 6a1.75 2.25 0 1 0 3.5 0a1.75 2.25 0 1 0-3.5 0Z");
}

</style>
