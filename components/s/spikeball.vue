<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i22926b3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:spikeball" /></template>
<style>
.i22926b3o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 16a9.25 4 0 1 0 18.5 0a9.25 4 0 1 0-18.5 0ZM9 6a3 3 0 1 0 6 0a3 3 0 1 0-6 0ZM2.75 16h18.5M12 12v8");
}

</style>
