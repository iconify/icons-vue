<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kegw5cbeq"/><path class="mb1lhd4rz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:risk-level-medium" /></template>
<style>
.kegw5cbeq {
  fill: currentColor;
  d: path("M3 14h4v6.5H3Zm7-4.5h4v11h-4Z");
}

.mb1lhd4rz {
  d: path("M17 4h4v16.5h-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
