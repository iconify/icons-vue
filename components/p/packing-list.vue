<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="vs633bcuw"/><path class="i66-bd_qs"/><path class="f24m1hg9i"/><rect class="kanm6-chi"/><path class="k_-x-2_oy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:packing-list" /></template>
<style>
.f24m1hg9i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 7.5h4.5m-4.5 4h3");
}

.i66-bd_qs {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 7.5h.01m-.01 4h.01m-.01 4h.01");
}

.k_-x-2_oy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.75 16v-1.25a1 1 0 0 1 1-1h1.75a1 1 0 0 1 1 1V16");
}

.kanm6-chi {
  width: 7.25px;
  height: 5.25px;
  x: 14px;
  y: 16px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.25px;
}

.vs633bcuw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.75 21.25h-5a2 2 0 0 1-2-2V4.75a2 2 0 0 1 2-2h10.5a2 2 0 0 1 2 2v6.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
