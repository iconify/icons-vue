<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j_biiobgp"/><path class="u3449-bsg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shacket" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j_biiobgp {
  d: path("M9.5 2.75L5.5 4l-3 7.5l2.25 1.25L5.5 11v10.5h13V11l.75 1.75l2.25-1.25l-3-7.5l-4-1.25L12 7ZM12 7v14.5");
}

.u3449-bsg {
  d: path("M7.25 10h3v2.5l-1.5 1l-1.5-1Zm6.5 0h3v2.5l-1.5 1l-1.5-1Z");
}

</style>
