<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="evp6gbwdz"/><path class="f9esptb4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wrinkles" /></template>
<style>
.evp6gbwdz {
  d: path("M6.5 4h11a4 4 0 0 1 4 4v8a4 4 0 0 1-4 4h-11a4 4 0 0 1-4-4V8a4 4 0 0 1 4-4Z");
}

.f9esptb4o {
  d: path("M7 8q1.25-1.25 2.5 0T12 8t2.5 0T17 8M7 12q1.25-1.25 2.5 0t2.5 0t2.5 0t2.5 0M7 16q1.25-1.25 2.5 0t2.5 0t2.5 0t2.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
