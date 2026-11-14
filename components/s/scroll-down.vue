<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ix-ech3bk"/><path class="qa4mrqbnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scroll-down" /></template>
<style>
.ix-ech3bk {
  d: path("M6.5 17V4.5a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2V17M4 17h16v4.5H4Zm8-11v7.5");
}

.qa4mrqbnr {
  d: path("M9.25 10.75L12 13.5l2.75-2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
