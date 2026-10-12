<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="knlwatbrb"/><path class="h3affsdku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oboe" /></template>
<style>
.h3affsdku {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 9.5h.01m3.24 3.25h.01");
}

.knlwatbrb {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.52 5.04l9.69 9.69q.53.53 1.21.85l2.02.98q.68.32.15.85l-3.18 3.18q-.53.53-.85-.15l-.98-2.02q-.32-.68-.85-1.21L5.04 7.52q-.53-.53 0-1.06l1.42-1.42q.53-.53 1.06 0m-1.77.71l-2.5-2.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
