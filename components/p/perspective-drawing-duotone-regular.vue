<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ibuanu9pl"/><path class="klh0dobdz"/><path class="s33347biw"/><path class="fm49t10dd"/><path class="dd2oi04rr"/><path class="mqtixbwqo"/><path class="lzdsnnb7v"/><path class="m91y9qbhe"/><path class="gbxzirw0u"/><path class="rkhcgsbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:perspective-drawing-duotone-regular" /></template>
<style>
.dd2oi04rr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fm49t10dd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M21 19 11 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gbxzirw0u {
  d: path("M21 19 11 9");
}

.ibuanu9pl {
  fill: currentColor;
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.klh0dobdz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 8h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lzdsnnb7v {
  d: path("M11 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.m91y9qbhe {
  d: path("M3 19 13 9");
}

.mqtixbwqo {
  d: path("M2 8h20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.s33347biw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 19 13 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
