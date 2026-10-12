<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="p95o4hbbt"/><path class="j985bibko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:package-keep-dry-sharp" /></template>
<style>
.j985bibko {
  d: path("M6.5 12a5.5 5.5 0 0 1 11 0Zm5.5 0v5.5H9.5v-1.25");
}

.p95o4hbbt {
  d: path("M2.75 3.75h18.5v17.5H2.75z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
