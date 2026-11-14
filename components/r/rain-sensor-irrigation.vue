<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zipinwc4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rain-sensor-irrigation" /></template>
<style>
.zipinwc4x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 11h11v5h-11ZM9 16v5.5m0-19s-2.25 2.75-2.25 4a2.25 2.25 0 0 0 4.5 0c0-1.25-2.25-4-2.25-4Zm7.798 9.072a3 3 0 0 1 0 3.856m2.298-5.785a6 6 0 0 1 0 7.714");
}

</style>
