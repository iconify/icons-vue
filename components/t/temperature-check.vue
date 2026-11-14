<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g7_-2rb4f"/><path class="d0q6t93hl"/><path class="s6_k0cb0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:temperature-check" /></template>
<style>
.d0q6t93hl {
  d: path("m20.268 1.964l1.768 1.768l-5.304 5.304l-1.768-1.768Z");
}

.g7_-2rb4f {
  d: path("M7 21.5V18c-2-1.5-2.75-3.5-2.75-5.75c0-3.75 2.75-6.5 6.25-6.5s6 2.25 6 5.75l1.25 3q.375.75-.75.75h-.5v2c0 1-.75 1.75-1.75 1.75H13v2.5");
}

.s6_k0cb0b {
  fill: currentColor;
  d: path("M14.5 8.25a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
