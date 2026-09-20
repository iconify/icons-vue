<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lsln50bxj"/><path class="ydkgc70eo"/><path class="fb6pq9bik"/><path class="l4pybmb4a"/><path class="syw99xh-n"/><path class="hac_zt_2k"/><path class="e325robmt"/><path class="xrit8bb9e"/><path class="ltxni2ncy"/><path class="zjf1fhb5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rater-duotone-thin" /></template>
<style>
.e325robmt {
  d: path("M3 13a4 4 0 0 1 8 0");
}

.fb6pq9bik {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 7h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hac_zt_2k {
  d: path("M5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l4pybmb4a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 12h7");
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

.syw99xh-n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 17h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xrit8bb9e {
  d: path("M14 7h7");
}

.ydkgc70eo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 13a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zjf1fhb5j {
  d: path("M14 17h5");
}

</style>
