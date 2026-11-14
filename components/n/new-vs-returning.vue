<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tieyokovm"/><path class="ntinobcbz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:new-vs-returning" /></template>
<style>
.ntinobcbz {
  d: path("M9 8.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm-2.25 8.5c0-2.5 2.25-4 4.75-4c1.469 0 2.851.518 3.742 1.452M18 14.5v7M14.5 18h7");
}

.tieyokovm {
  d: path("M8.922 20.457a9 9 0 1 1 12.044-9.241m-2.216-.966l1.644 1.462m.374.332l.232.206l1-2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
