<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ai0nwsbln"/><path class="a29ib3d7y"/><path class="mvoyk1oek"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:returns-cage" /></template>
<style>
.a29ib3d7y {
  d: path("M10 9h3a1.75 1.75 0 0 1 0 3.5h-2.5");
}

.ai0nwsbln {
  d: path("M3.5 2.5h17v16h-17Zm4 0v16m9-16v16m-13-12h17m-17 8h17");
}

.mvoyk1oek {
  d: path("M11.25 7.75L10 9l1.25 1.25m-6 10.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Zm11 0a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
