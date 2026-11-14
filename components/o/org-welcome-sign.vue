<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k1gbqcsqe"/><path class="s90ol2w0k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:org-welcome-sign" /></template>
<style>
.k1gbqcsqe {
  d: path("M2.5 3.5h19v11h-19Zm4 11v7m11-7v7");
}

.s90ol2w0k {
  d: path("M12 12.25c-1.5-1-3.25-2.25-3.25-4C8.75 7 9.75 6 11 6c.5 0 .75.25 1 .75c.25-.5.5-.75 1-.75c1.25 0 2.25 1 2.25 2.25c0 1.75-1.75 3-3.25 4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
