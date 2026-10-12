<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="jo6p1ypzw"/><path class="h3affsdku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oboe-sharp" /></template>
<style>
.h3affsdku {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 9.5h.01m3.24 3.25h.01");
}

.jo6p1ypzw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.52 5.04l9.69 9.69l.53.53l.68.32l2.02.98l.68.32l-.53.53l-3.18 3.18l-.53.53l-.32-.68l-.98-2.02l-.32-.68l-.53-.53l-9.69-9.69l-.53-.53l.53-.53l1.42-1.42l.53-.53zm-1.77.71l-2.5-2.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
