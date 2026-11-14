<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="i5pptlbrt"/><path class="eeu62bz4i"/><path class="enlsfwz2r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:parser" /></template>
<style>
.eeu62bz4i {
  d: path("M3 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-2 5.5v-1.75h8v1.75M15 14v1.75");
}

.enlsfwz2r {
  d: path("M9 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm8 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.i5pptlbrt {
  d: path("M8 4.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM5 10V8.25h10V10m-5-3.5v1.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
