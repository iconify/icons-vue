<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tbqyphbio"/><path class="limx7sbdb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rocket-launch" /></template>
<style>
.limx7sbdb {
  d: path("M11 9H7l2 2m6 2v4l-2-2m-8.5 6c-2 0-2-3 0-3c0-2.5 3.5-3 4-1c2 0 2 4 0 4Z");
}

.tbqyphbio {
  d: path("m9 11l5-5q3.5-2.5 5.5-1.5q1 2-1.5 5.5l-5 5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
