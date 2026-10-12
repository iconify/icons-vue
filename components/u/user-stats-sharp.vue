<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="rknchmb5r"/><path class="smj5mackf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-stats-sharp" /></template>
<style>
.rknchmb5r {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.75px;
}

.smj5mackf {
  d: path("M4 20.25h11.75v-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5v.75zm11.5-5.75v-2m2.75 2V10M21 14.5v-7");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
