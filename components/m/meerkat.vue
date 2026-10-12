<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="w50z9ub_z"/><path class="fy-m9id4m"/><path class="al12gft3b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:meerkat" /></template>
<style>
.al12gft3b {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.75 4.75h.01");
}

.fy-m9id4m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.75 10.75c.5 1 1.5 1.5 2.5 1.5m1.5 8c2 0 3.75-.5 5-1.75");
}

.w50z9ub_z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 5.5c0-.5.3-.85.75-1l2.25-.9c.5-.6 1.25-.85 2-.85c1.4 0 2.5 1.1 2.5 2.5v2.5c1.25 2 1.75 4.5 1.75 7.25q0 3-.75 5.25h-5.5c-.5-1.75-.75-3.75-.75-5.75c0-2.25.5-4.25 1.25-6L7 6.5c-.45-.1-.75-.5-.75-1");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
