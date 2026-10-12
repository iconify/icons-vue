<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="yktxy1hlr"/><path class="ni03p4sii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:treble-clef" /></template>
<style>
.ni03p4sii {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.6 9.6h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yktxy1hlr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 20.5c.4.55.95.75 1.5.75c.95 0 1.55-.7 1.4-1.7L10.9 4.75c-.15-1.15.45-2 1.35-2c1.1 0 1.75 1.05 1.75 2.4c0 2.35-2.05 3.6-3.9 5c-1.75 1.35-3.35 2.6-3.35 4.85c0 2.3 1.95 3.75 4.25 3.75c2.35 0 4.25-1.4 4.25-3.6c0-2.1-1.75-3.3-3.6-3.3");
}

</style>
