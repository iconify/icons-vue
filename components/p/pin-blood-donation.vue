<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="b3anb2b2e"/><path class="cu_5zq69p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-blood-donation" /></template>
<style>
.b3anb2b2e {
  d: path("m9.5 19.5l-5-7a6.25 6.25 0 1 1 10 0Z");
}

.cu_5zq69p {
  d: path("M7.25 8.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm11 5.75s3 3 3 4a3 3 0 0 1-6 0c0-1 3-4 3-4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
