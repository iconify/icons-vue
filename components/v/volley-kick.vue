<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bkbe37b-t"/><path class="b23exnb-t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:volley-kick" /></template>
<style>
.b23exnb-t {
  d: path("M13.25 8.75q3.75-2.25 7.5 0");
}

.bkbe37b-t {
  d: path("M4 5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2.5 5.25l1 4.25l-2 7m2-7l5 1.75l2-2.75M13 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
