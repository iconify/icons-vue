<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yk4uotjjx"/><path class="p-jb5ov2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:toy-mouse" /></template>
<style>
.p-jb5ov2i {
  d: path("M6.25 9.5a2.5 2.5 0 1 1 4-1.5m3.5 0a2.5 2.5 0 1 1 3 1.25m2.25 5.5c3 0 3 4.25-.5 4.5c-2.5.25-4-1.25-6 .25M8 12h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yk4uotjjx {
  d: path("M3 14.75c1-4.5 5-7 9-7c4.5 0 7 3 7 7Z");
}

</style>
