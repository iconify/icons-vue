<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ja5un3p0l"/><circle class="fs6wrlbbp"/><path class="xmrzk9b5p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:spending-limit-sharp" /></template>
<style>
.fs6wrlbbp {
  cx: 12px;
  cy: 14.75px;
  r: 6px;
}

.ja5un3p0l {
  d: path("M3 11V5.75h18V11");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xmrzk9b5p {
  d: path("m13.81 13.29l-.435-1.08H10.39v1.33c0 1.77 3.56.99 3.56 2.88v1.36h-3.18l-.54-1.08");
}

</style>
