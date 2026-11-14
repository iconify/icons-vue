<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lrjjl12fa"/><path class="o9ytzybgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-pin-house" /></template>
<style>
.lrjjl12fa {
  d: path("M13.075 20H5q-.098 0-.195-.019t-.188-.057t-.173-.093q-.081-.054-.151-.124t-.124-.151q-.055-.082-.093-.173t-.057-.188T4 19v-8.5l8-7l8 7v1.04");
}

.o9ytzybgw {
  d: path("M18 21.5S15 19 15 17a3 3 0 0 1 6 0c0 2-3 4.5-3 4.5Zm0-4.5h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
