<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="bh4biibbp"/><path class="tjepotari"/><path class="zhuhsu4bq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vote-check-sharp" /></template>
<style>
.bh4biibbp {
  d: path("M4.75 2.75h14.5v18.5H4.75z");
}

.tjepotari {
  d: path("M7.75 6h2.5v2.5h-2.5zm0 5h2.5v2.5h-2.5zm0 5h2.5v2.5h-2.5zm5-3.75h3.5m-3.5 5h3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zhuhsu4bq {
  d: path("m7.5 7.25l1.75 2l5.5-6");
}

</style>
