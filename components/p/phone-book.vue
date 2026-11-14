<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fdp145m5v"/><path class="p1nhhq6mm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:phone-book" /></template>
<style>
.fdp145m5v {
  d: path("M3 2.5h18v19H3Zm3.5 0v19");
}

.p1nhhq6mm {
  d: path("M11.75 7.75q.75 0 .75.75l.25 1.5c.25.25 0 .5-.25.75l-.75.5c.5 1.25 1.25 2 2.5 2.5l.5-.75c.25-.25.5-.5.75-.25L17 13q.75 0 .75.75v1.5c0 .5-.5 1-1 1c-4 0-7.5-3.5-7.5-7.5c0-.5.5-1 1-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
