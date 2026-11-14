<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="m3dz1ybbb"/><path class="kk7wujc5a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:potted-succulent" /></template>
<style>
.kk7wujc5a {
  d: path("M11 14.5c-4 0-6.5-2.5-7-6c3.5.5 6 2.5 7 6Zm2 0c4 0 6.5-2.5 7-6c-3.5.5-6 2.5-7 6Z");
}

.m3dz1ybbb {
  d: path("M5.5 14.5h13l-1.75 7h-9.5Zm6.5 0C9.5 12 9.5 8 12 4.5c2.5 3.5 2.5 7.5 0 10Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
