<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pw7p-85ys"/><path class="zch0gipxa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:watermark-ai-sharp" /></template>
<style>
.pw7p-85ys {
  d: path("M2.75 3.75h18.5v16.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zch0gipxa {
  d: path("m2.75 17.25l5-5l5.5 5.5M16 6.5c1.75 2 2.75 3.5 2.75 4.75a2.75 2.75 0 0 1-5.5 0c0-1.25 1-2.75 2.75-4.75Z");
}

</style>
