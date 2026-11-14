<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jvdsyy1hl"/><path class="vqdo05bst"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:rearview-mirror" /></template>
<style>
.jvdsyy1hl {
  d: path("m2.5 19l2-14.5q7.5-1.5 15 0l2 14.5q-9.5-1.5-19 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vqdo05bst {
  d: path("M6.5 8.5h11v5h-11ZM12 3.75V8.5");
}

</style>
