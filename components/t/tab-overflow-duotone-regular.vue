<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tyien_b-s"/><path class="y1xrshbyn"/><path class="rxfmyhero"/><path class="rsxmkkb6q"/><path class="mbt4yzbhr"/><path class="oscmqi7_r"/><path class="z9ittvbis"/><path class="yegul17ht"/><path class="ec5tld62j"/><path class="gju7e2bvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tab-overflow-duotone-regular" /></template>
<style>
.ec5tld62j {
  d: path("M17 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.gju7e2bvn {
  d: path("M20 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mbt4yzbhr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oscmqi7_r {
  d: path("M2 19V9l2 -2h6l2 2v10");
}

.rsxmkkb6q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19V9l2 -2h6l2 2v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rxfmyhero {
  fill: currentColor;
  d: path("M20 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tyien_b-s {
  fill: currentColor;
  d: path("M14 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.y1xrshbyn {
  fill: currentColor;
  d: path("M17 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yegul17ht {
  d: path("M14 13a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
