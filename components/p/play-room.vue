<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nekneubfb"/><path class="emxmgobwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:play-room" /></template>
<style>
.emxmgobwc {
  d: path("m14.5 9.5l2-4.75c.5-1.25 2.25-1.5 3.25-.5L21 5.75L18.75 7l-1 3M7.5 14L6 18m8.5-4l1.5 4M2.5 16.75c4.5 3.75 14.5 3.75 19 0M6 11L3.25 9");
}

.nekneubfb {
  d: path("M6 9.5h10V14H6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
