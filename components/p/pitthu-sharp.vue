<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="u-ml0ubfo"/><circle class="zgau9oblh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pitthu-sharp" /></template>
<style>
.u-ml0ubfo {
  d: path("M3.75 17.5h13v3.75h-13zm1.5-3.75h10v3.75h-10zM6.75 10h7v3.75h-7z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zgau9oblh {
  cx: 18px;
  cy: 6px;
  r: 3.25px;
}

</style>
