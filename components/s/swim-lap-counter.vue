<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itf7giaql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:swim-lap-counter" /></template>
<style>
.itf7giaql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7a3 2.5 0 1 0 6 0a3 2.5 0 1 0-6 0Zm6 0a3 2.5 0 1 0 6 0a3 2.5 0 1 0-6 0Zm6 0a3 2.5 0 1 0 6 0a3 2.5 0 1 0-6 0Zm-12 8q2.25-1.5 4.5 0t4.5 0m4 .5a2.75 2.75 0 0 1 5.5 0c0 2.25-5.5 3.5-5.5 6h5.75");
}

</style>
