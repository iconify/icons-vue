<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hq8u2ob3y"/><path class="gzmu5fb2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-pond" /></template>
<style>
.gzmu5fb2a {
  d: path("M7.5 15.25q2.25-.75 4.5 0t4.5 0m-6.5 3q1.5-.75 3 0t3 0M8 6h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hq8u2ob3y {
  d: path("M2.5 17a9.5 4.5 0 1 0 19 0a9.5 4.5 0 1 0-19 0m2-10.5c3-4.5 8-4.5 10.5 0L19.5 3v7L15 6.5C12.5 11 7.5 11 4.5 6.5");
}

</style>
