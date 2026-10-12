<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m72yl7mlv"/><path class="zl4n61bpq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mention-sharp" /></template>
<style>
.m72yl7mlv {
  d: path("M12 3.25c4.85 0 8.75 3.5 8.75 7.85s-3.9 7.85-8.75 7.85h-1.616l-1.484-.5L4.6 20l-1.57.523l.67-1.473l1.2-2.9c-1-1.4-1.65-3.15-1.65-5.05c0-4.35 3.9-7.85 8.75-7.85Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zl4n61bpq {
  d: path("M13.75 11.1a1.75 1.75 0 1 1-3.5 0a1.75 1.75 0 0 1 3.5 0Zm0 0v2.25h2.75V11.1a4.5 4.5 0 1 0-1.75 3.55");
}

</style>
