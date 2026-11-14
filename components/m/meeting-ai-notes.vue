<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dm4x38bzy"/><path class="y1b_bn4lx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:meeting-ai-notes" /></template>
<style>
.dm4x38bzy {
  d: path("M11.5 18.5h-9V4H21v7.3M6 7.75h11.5M6 11h8.5M6 14.25h4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y1b_bn4lx {
  d: path("M15.25 14H20a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1h-2.75l-2 2v-2a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1Z");
}

</style>
