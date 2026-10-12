<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="v09w203dx"/><path class="bhndxabjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-video-sharp" /></template>
<style>
.bhndxabjf {
  d: path("M4 20.25h11.75v-.75c0-3-2.8-5.25-6.25-5.25S3.25 16.5 3.25 19.5v.75zM14.75 9.5h3.75v4.25h-3.75zm3.75 1.25l2.75-1.5V14l-2.75-1.5");
}

.v09w203dx {
  cx: 9.5px;
  cy: 7.75px;
  r: 3.25px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
