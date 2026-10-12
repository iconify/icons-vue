<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wivst-byx"/><path class="hxyj34brl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smart-kettle-sharp" /></template>
<style>
.hxyj34brl {
  d: path("M8.5 9.5V8a3.5 3.5 0 0 1 7 0v1.5M5.25 14.25l-2.5-2.75m2.75 1.75h13");
}

.wivst-byx {
  d: path("M6.25 21.25h11.5l1.607.004l-.107-1.604l-.6-6.9l-.234-3.508l-3.516.008H9.1l-3.516-.008l-.234 3.508l-.6 6.9l-.107 1.604z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
