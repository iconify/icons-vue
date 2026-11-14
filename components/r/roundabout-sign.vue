<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="il-rnqb5b"/><path class="dpqphz1ah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:roundabout-sign" /></template>
<style>
.dpqphz1ah {
  d: path("M13.75 7.25A5 5 0 0 1 17 12m-1.75-1.75L17 12l1.75-1.75m-3.5 5.5a5 5 0 0 1-5.75.5m2.5-.5l-2.5.5l.75 2.5m-3.25-6a5 5 0 0 1 2.5-5M8.75 10l.75-2.25L7 7");
}

.il-rnqb5b {
  d: path("M2.25 12a9.75 9.75 0 1 0 19.5 0a9.75 9.75 0 1 0-19.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
