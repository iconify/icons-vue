<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="brjfxpbbs"/><path class="cfybrac7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:popcorn-maker" /></template>
<style>
.brjfxpbbs {
  d: path("M3 14h18l-1.5 5.5a2 2 0 0 1-2 1.5h-11a2 2 0 0 1-2-1.5Zm0 0a9 9 0 0 1 18 0M12 2.5V5");
}

.cfybrac7m {
  d: path("M8 11.5a2 2 0 0 1 2-2.75a2.25 2.25 0 0 1 4 0a2 2 0 0 1 2 2.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
