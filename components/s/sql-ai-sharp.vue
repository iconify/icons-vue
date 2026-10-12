<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="yu68wubfq"/><path class="sw806k7ry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sql-ai-sharp" /></template>
<style>
.sw806k7ry {
  d: path("M3 6.25c.7 1.5 3.15 2.5 6 2.5s5.3-1 6-2.5m-12 6c.7 1.5 3.15 2.5 6 2.5m9.25.5l.36 2.64l2.64.36l-2.64.36l-.36 2.64l-.36-2.64l-2.64-.36l2.64-.36z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yu68wubfq {
  d: path("M2.75 5.75c0-1.75 2.8-3 6.25-3s6.25 1.25 6.25 3v12.5c0 1.75-2.8 3-6.25 3s-6.25-1.25-6.25-3Z");
}

</style>
