<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w8gn0cc8z"/><path class="zu3q095pr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:weak-link" /></template>
<style>
.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w8gn0cc8z {
  d: path("M3.5 9H11a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H3.5a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1Z");
}

.zu3q095pr {
  d: path("M14.528 15H13q-.098 0-.195-.019t-.188-.057t-.173-.093t-.151-.124t-.124-.151t-.093-.173t-.057-.188T12 14v-4q0-.098.019-.195t.057-.188t.093-.173t.124-.151t.151-.124t.173-.093t.188-.057T13 9m5.9 0h1.6q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188t.019.195v4q0 .098-.019.195t-.057.188t-.093.173q-.054.081-.124.151t-.151.124q-.082.055-.173.093t-.188.057T20.5 15h-.172M17 5.5l-1.5 5L18 13l-1.5 5.5");
}

</style>
