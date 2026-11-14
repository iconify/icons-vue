<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p38mb9bkc"/><path class="qk_nzqwoy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ski-rack" /></template>
<style>
.p38mb9bkc {
  d: path("M5 19H3.5q-1 0-1-1v-3.5q0-1.25 1.25-1.5l2.75-.5L9 9.25q.5-.75 1.5-.75H15q1 0 1.5.75l2.75 3.25l1 .25q1.25.25 1.25 1.75V18q0 1-1 1H19a2 2 0 0 0-4 0H9a2 2 0 0 0-4 0Z");
}

.qk_nzqwoy {
  d: path("M5 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0ZM3 5.75h16q1.75 0 2.25-1.75M3 2.75h14m-6.5 3V8.5M15 5.75V8.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
