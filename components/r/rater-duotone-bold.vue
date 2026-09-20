<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lsln50bxj"/><path class="wlci694hy"/><path class="hd70ypjkf"/><path class="mjobmmu8w"/><path class="af_6vyb5b"/><path class="hac_zt_2k"/><path class="e325robmt"/><path class="xrit8bb9e"/><path class="ltxni2ncy"/><path class="zjf1fhb5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rater-duotone-bold" /></template>
<style>
.af_6vyb5b {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 17h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e325robmt {
  d: path("M3 13a4 4 0 0 1 8 0");
}

.hac_zt_2k {
  d: path("M5 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hd70ypjkf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 7h7");
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

.mjobmmu8w {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 12h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wlci694hy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 13a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xrit8bb9e {
  d: path("M14 7h7");
}

.zjf1fhb5j {
  d: path("M14 17h5");
}

</style>
