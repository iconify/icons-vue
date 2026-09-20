<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y1nfwg_iv"/><path class="d5b4fcc2f"/><path class="omdp355hx"/><path class="s2n9l4i0j"/><path class="k187sabpz"/><path class="z9ittvbis"/><path class="mia87q3wc"/><path class="a1mgubcgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pantry-duotone-bold" /></template>
<style>
.a1mgubcgh {
  d: path("M13 19v-5h4v5");
}

.d5b4fcc2f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k187sabpz {
  d: path("M2 11h20");
}

.mia87q3wc {
  d: path("M5 11V6h4v5");
}

.omdp355hx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 11V6h4v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s2n9l4i0j {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 19v-5h4v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y1nfwg_iv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 11h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
