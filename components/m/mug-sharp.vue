<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="w4lzazb6m"/><path class="t62mnwbtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mug-sharp" /></template>
<style>
.t62mnwbtr {
  d: path("m10 16l-2.1-2.1a1.3 1.3 0 0 1 2.1-1.6a1.3 1.3 0 0 1 2.1 1.6Z");
}

.w4lzazb6m {
  d: path("M3.75 4.75h12.5v16.5H3.75zm12.5 4h4.5v8h-4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
