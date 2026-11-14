<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z1pvq-bfb"/><path class="e1d_314nu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pothole-repair" /></template>
<style>
.e1d_314nu {
  d: path("M10 10h4v4a2 2 0 0 1-4 0Zm2 0V4.5m-2.25 0h4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z1pvq-bfb {
  d: path("M2.5 14h4q5.5 10 11 0h4");
}

</style>
