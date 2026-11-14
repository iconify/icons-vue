<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d7wu2fffq"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tooth-clock" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.d7wu2fffq {
  d: path("M19.183 12.04C19.602 10.756 20 9.577 20 8c0-2.5-1-4.5-3.5-4.5c-2 0-3 1-4.5 1s-2.5-1-4.5-1C5 3.5 4 5.5 4 8s1 4 1.5 6.5l1 5c.25 1.25 1.75 1.25 2 0l1-4.5c.25-1 1.25-1.5 2.5-1.5c.602 0 1.146.116 1.576.348M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
