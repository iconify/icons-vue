<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ots31sbwo"/><path class="nnspmd9st"/><path class="bjqnciocz"/><path class="jd_dotbnq"/><path class="m6dxv6big"/><path class="n415dkmtk"/><path class="drwyp5bdd"/><path class="c7z9o8buo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tax-included-duotone-thin" /></template>
<style>
.bjqnciocz {
  fill: currentColor;
  d: path("M13.5 11.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.c7z9o8buo {
  d: path("M7 15h10");
}

.drwyp5bdd {
  d: path("M13.5 11.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jd_dotbnq {
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
}

.m6dxv6big {
  d: path("M8.5 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.n415dkmtk {
  d: path("m8.5 13 7 -7");
}

.nnspmd9st {
  fill: currentColor;
  d: path("M8.5 7.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ots31sbwo {
  fill: currentColor;
  d: path("M6 2h12a2 2 0 0 1 2 2v15l-2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2 -2 -2 -2 2V4a2 2 0 0 1 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
