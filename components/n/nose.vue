<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="kvc7j1bsi"/><path class="qqimkdb8a"/><path class="prc1ybcum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:nose" /></template>
<style>
.kvc7j1bsi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 2.75c0 4.5-1 7.75-3.5 11c-1.25 1.75-.25 4.75 2 4.75h6c2.25 0 3.25-3 2-4.75c-2.5-3.25-3.5-6.5-3.5-11");
}

.prc1ybcum {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.75a1.75 2.5 0 0 1 3.5 0v1.5a1.75 2.5 0 0 1-3.5 0Zm15 0a1.75 2.5 0 0 1 3.5 0v1.5a1.75 2.5 0 0 1-3.5 0Z");
}

.qqimkdb8a {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 16h.01M14 16h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
