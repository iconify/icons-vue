<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j5kmrzkzz"/><path class="nywht6bzt"/><path class="o0obawb-d"/><path class="ke67hpbif"/><path class="i2opcxb3r"/><path class="vj0y8fbql"/><path class="sh5dclbup"/><path class="v2maedbuw"/><path class="f-g8rrj2k"/><path class="zn7ywxs2s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:selection-box-duotone-regular" /></template>
<style>
.f-g8rrj2k {
  d: path("M2 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.i2opcxb3r {
  fill: currentColor;
  d: path("M20 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.j5kmrzkzz {
  fill: currentColor;
  d: path("M6 8a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ke67hpbif {
  fill: currentColor;
  d: path("M2 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nywht6bzt {
  fill: currentColor;
  d: path("M2 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o0obawb-d {
  fill: currentColor;
  d: path("M20 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.sh5dclbup {
  d: path("M2 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.v2maedbuw {
  d: path("M20 3a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.vj0y8fbql {
  d: path("M6 8a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.zn7ywxs2s {
  d: path("M20 21a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
