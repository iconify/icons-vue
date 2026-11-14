<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d_n-bobui"/><path class="xsj2_c9wz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:themed-costume" /></template>
<style>
.d_n-bobui {
  d: path("M3.5 5q7.5-3 15 0v6c0 6-4 10.5-7.5 10.5S3.5 17 3.5 11Zm15 4l3 3m-3-3l2 5.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xsj2_c9wz {
  d: path("M6 10a1.75 1.5 0 1 0 3.5 0A1.75 1.5 0 1 0 6 10Zm6.5 0a1.75 1.5 0 1 0 3.5 0a1.75 1.5 0 1 0-3.5 0Z");
}

</style>
