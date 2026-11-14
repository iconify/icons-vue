<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sc5lc9t2i"/><path class="nm-ll_1_l"/><path class="r3cb0nukc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:news-agency" /></template>
<style>
.nm-ll_1_l {
  d: path("M14.5 2.5v5h5m-11.75 7a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Z");
}

.r3cb0nukc {
  d: path("M10 14.5a2 4.25 0 1 0 4 0a2 4.25 0 1 0-4 0Z");
}

.sc5lc9t2i {
  d: path("M4.5 4A1.5 1.5 0 0 1 6 2.5h8.5l5 5V20a1.5 1.5 0 0 1-1.5 1.5H6A1.5 1.5 0 0 1 4.5 20Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
