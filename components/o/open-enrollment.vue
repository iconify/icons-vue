<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ny2hrqbyd"/><path class="wm18w-cil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:open-enrollment" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ny2hrqbyd {
  d: path("M5.125 2.5h13.75A2.625 2.625 0 0 1 21.5 5.125v13.75a2.625 2.625 0 0 1-2.625 2.625H5.125A2.625 2.625 0 0 1 2.5 18.875V5.125A2.625 2.625 0 0 1 5.125 2.5M2.5 5.5h19m-19 3h19");
}

.wm18w-cil {
  d: path("M7.5 14h9a1.5 1.5 0 0 1 1.5 1.5V20a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 6 20v-4.5A1.5 1.5 0 0 1 7.5 14m4.5 0v7.5m0-7.5c-1.25-2.25-3.5-2.75-3.5-1.25c0 1 2 1.25 3.5 1.25s3.5-.25 3.5-1.25c0-1.5-2.25-1-3.5 1.25");
}

</style>
