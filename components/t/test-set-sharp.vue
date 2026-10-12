<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="cli8d0xzk"/><path class="c_4hrcb3k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:test-set-sharp" /></template>
<style>
.c_4hrcb3k {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19 8h.01M19 12h.01M19 16h.01");
}

.cli8d0xzk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h11.5v16.5H2.75zM6.25 8h5m-5 4h5m-5 4h5m5.5-12.25h4.5v16.5h-4.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
