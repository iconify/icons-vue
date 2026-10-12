<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mxtc64b7q"/><path class="u9o849bfm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wide-door" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mxtc64b7q {
  d: path("M3.75 21.25V4.75a2 2 0 0 1 2-2h12.5a2 2 0 0 1 2 2v16.5m-17.5 0h18.5");
}

.u9o849bfm {
  d: path("M7 12h10m-8-2l-2 2l2 2m6-4l2 2l-2 2");
}

</style>
