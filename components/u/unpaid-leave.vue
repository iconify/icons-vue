<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="trh2ghbkw"/><path class="p6wziqj4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:unpaid-leave" /></template>
<style>
.p6wziqj4l {
  d: path("M10 6.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm4 0h3.5M9.25 15a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Zm.5 2.75l4.5-5.5");
}

.trh2ghbkw {
  d: path("M6.5 2.5h11v19h-11Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
