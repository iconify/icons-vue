<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="xkosebb9k"/><path class="fzfa9xrtu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:upvote-sharp" /></template>
<style>
.fzfa9xrtu {
  d: path("M9.75 15.5L12 13.25l2.25 2.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xkosebb9k {
  d: path("m13.05 3.83l6.9 7.09L21 12h-5v9.25H8V12H3l1.05-1.08l6.9-7.09L12 2.75z");
}

</style>
