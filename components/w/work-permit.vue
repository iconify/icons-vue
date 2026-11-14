<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pjahc7pbp"/><path class="nlaq1-bus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:work-permit" /></template>
<style>
.nlaq1-bus {
  d: path("M10.5 17.75a1.5 3.75 0 1 0 3 0a1.5 3.75 0 1 0-3 0Zm-2.25 0h7.5");
}

.pjahc7pbp {
  d: path("M10 2.5h4v6h-4Zm-4.5 6h13V11h-13Zm2.75 9.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
