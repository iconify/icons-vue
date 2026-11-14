<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="imrv2acqz"/><path class="qbr01_b7t"/><path class="i-0s5h1ic"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:priority-matrix" /></template>
<style>
.i-0s5h1ic {
  d: path("M3 14h7v7H3Zm11 0h7v7h-7Z");
}

.imrv2acqz {
  d: path("M3 3h7v7H3Z");
}

.qbr01_b7t {
  fill: currentColor;
  d: path("M14 3h7v7h-7Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
