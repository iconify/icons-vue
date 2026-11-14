<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ikhl1g6lx"/><path class="u19-hpb3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sports-podcast" /></template>
<style>
.ikhl1g6lx {
  d: path("M7.5 2.5h4a1 1 0 0 1 1 1V12a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V3.5a1 1 0 0 1 1-1Z");
}

.u19-hpb3x {
  d: path("M3.5 10a6 6 0 0 0 12 0m-6 6v5.5m9-3h.01m-2.26-2.25a3.25 3.25 0 0 0 0 4.5m4.5-4.5a3.25 3.25 0 0 1 0 4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
