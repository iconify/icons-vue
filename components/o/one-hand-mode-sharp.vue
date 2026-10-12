<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m6dc86yhg"/><path class="fsrhlacof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:one-hand-mode-sharp" /></template>
<style>
.fsrhlacof {
  d: path("M5.75 11h12.5v10.25H5.75zM12 5.25v3.5M10.25 7L12 8.75L13.75 7");
}

.m6dc86yhg {
  d: path("M5.75 12.5V2.75h12.5v9.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
