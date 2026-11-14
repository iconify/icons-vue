<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx2w229mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mesh-node-offline" /></template>
<style>
.rx2w229mc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.75 7.25l-4.5 8.5m7-8.5l4 8M7.5 18h8m-6-13a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-7 13a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm13 0a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm5-2l-4 4");
}

</style>
