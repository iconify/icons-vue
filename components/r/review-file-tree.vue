<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tavlno-ue"/><path class="x6jua0bmq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:review-file-tree" /></template>
<style>
.tavlno-ue {
  d: path("M3 6a2 2 0 0 1 2-2h4.5l2 2H19a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x6jua0bmq {
  d: path("M7 8.75v7h7.5M7 11h3.5m0 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm4 4.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

</style>
