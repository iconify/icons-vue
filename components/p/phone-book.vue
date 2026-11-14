<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x4ke-bx1b"/><path class="p1nhhq6mm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:phone-book" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p1nhhq6mm {
  d: path("M11.75 7.75q.75 0 .75.75l.25 1.5c.25.25 0 .5-.25.75l-.75.5c.5 1.25 1.25 2 2.5 2.5l.5-.75c.25-.25.5-.5.75-.25L17 13q.75 0 .75.75v1.5c0 .5-.5 1-1 1c-4 0-7.5-3.5-7.5-7.5c0-.5.5-1 1-1Z");
}

.x4ke-bx1b {
  d: path("M6.5 2.5h11A3.5 3.5 0 0 1 21 6v12a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 18V6a3.5 3.5 0 0 1 3.5-3.5m0 0v19");
}

</style>
