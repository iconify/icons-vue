<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ez1f0isbh"/><path class="jdupctu0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:whole-note-sharp" /></template>
<style>
.ez1f0isbh {
  d: path("M4.5 12a7.5 5.25 0 1 0 15 0a7.5 5.25 0 1 0-15 0Z");
}

.jdupctu0b {
  d: path("M9.89 13.77a2.75 1.75-40 1 0 4.22-3.54a2.75 1.75-40 1 0-4.22 3.54Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
