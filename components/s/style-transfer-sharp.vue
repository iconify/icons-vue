<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="rt0lizbtg"/><path class="jghqohuch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:style-transfer-sharp" /></template>
<style>
.jghqohuch {
  d: path("M6 6.25h.01m3.24-.5h.01m-2.76 4h.01M14.5 4.5h4.75v4.75m-1.75-1.5l1.75 1.75L21 7.75m-8.25 5h8.5v8.5h-8.5z");
}

.rt0lizbtg {
  cx: 7.75px;
  cy: 7.75px;
  r: 5px;
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
