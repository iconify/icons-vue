<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ce5j_sb9d"/><path class="rrnze4bye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:stomach-organ-sharp" /></template>
<style>
.ce5j_sb9d {
  d: path("M8 2.75h2.5V6l1.5-.75h2c3.75 0 6.25 3 6.25 7c0 4.75-3.75 8-8.25 8c-2 0-3.75-.75-4.75-1.75h-3.5V15h3.5l1.667 1.25h1.833c2.25 0 3.75-1.5 3.75-3.75c0-2-1.25-3.25-3-3.25h-1.25l-1.5 1L8 7.75Z");
}

.rrnze4bye {
  d: path("M3.75 17.25c-1 1.25-.75 4 1.5 4h2.5m7-11.75l.75-.75l.75.75l.75.75l.75-.75m-1.75 3l.75-.75l.75.75l.75.75l.75-.75m-4 3.25l.75-.75l.75.75l.75.75l.75-.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
