<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="r29buzb1t"/><path class="fx682i-nj"/><path class="w01ill24v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thinking" /></template>
<style>
.fx682i-nj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.25 9.5h.01m5.49 0h.01");
}

.r29buzb1t {
  cx: 12px;
  cy: 11px;
  r: 8px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w01ill24v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.75 6.5l2.5-.75m-2.75 8l2.75-.5M7.5 16.5h2v-1.1a1.13 1.13 0 0 1 2.25 0v3.85a2 2 0 0 1-2 2H7.5a2 2 0 0 1-2-2V19a2 2 0 0 1 2-2Z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
