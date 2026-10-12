<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bki_fti6o"/><path class="kmps77u7k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:redo-sharp" /></template>
<style>
.bki_fti6o {
  d: path("M19.75 9.25h-10a5.5 5.5 0 0 0 0 11H14");
}

.kmps77u7k {
  d: path("m15.75 5.25l4 4l-4 4");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
