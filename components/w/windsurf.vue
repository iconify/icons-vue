<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="p0tg2nbsm"/><path class="ffbur533g"/><path class="ned26cc6b"/><path class="vwhnxzn5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:windsurf" /></template>
<style>
.ffbur533g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13 11.25c1.75-.75 3.75-.5 5.25 1.25");
}

.ned26cc6b {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.75 7.5h.01");
}

.p0tg2nbsm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.25 3.25L11.1 15.5h8.65c-.6-4.75-2.25-9-5.5-12.25");
}

.vwhnxzn5j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7 9.75l1.9 9M7.4 11.5l4.35.25m-.65 3.75l-.85 3.5M3 19.75L21 18");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
