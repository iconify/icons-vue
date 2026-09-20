<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lsln50bxj"/><path class="jcq7_3bye"/><path class="fg6z65b1m"/><path class="ul1d350nr"/><path class="lyp9s4bvq"/><path class="hac_zt_2k"/><path class="e325robmt"/><path class="xrit8bb9e"/><path class="ltxni2ncy"/><path class="zjf1fhb5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rater-duotone-regular" /></template>
<style>
.e325robmt {
  d: path("M3 13a4 4 0 0 1 8 0");
}

.fg6z65b1m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 7h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hac_zt_2k {
  d: path("M5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.jcq7_3bye {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 13a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lsln50bxj {
  fill: currentColor;
  d: path("M5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ltxni2ncy {
  d: path("M14 12h7");
}

.lyp9s4bvq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 17h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ul1d350nr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xrit8bb9e {
  d: path("M14 7h7");
}

.zjf1fhb5j {
  d: path("M14 17h5");
}

</style>
