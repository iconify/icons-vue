<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xdnd0h2bk"/><path class="ujnxxccch"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pool-shower" /></template>
<style>
.ujnxxccch {
  d: path("M10 6h6l1.5 3h-9Zm0 6l-.5 2m3.5-2v3m3-3l.5 2");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xdnd0h2bk {
  d: path("M5 21V5a2 2 0 0 1 2-2h6v3");
}

</style>
