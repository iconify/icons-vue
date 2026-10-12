<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kgfb2rp5t"/><path class="tilxn3bvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sticky-note-x" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kgfb2rp5t {
  d: path("M5.75 3.75h12.5q2 0 2 2V13q0 2-1.41 3.41l-2.43 2.43Q15 20.25 13 20.25H5.75q-2 0-2-2V5.75q0-2 2-2");
}

.tilxn3bvx {
  d: path("M20.25 15H17a2 2 0 0 0-2 2v3.25M7.5 8.75h9m-9 3.75H13");
}

</style>
