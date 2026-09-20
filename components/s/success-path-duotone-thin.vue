<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pwjia2r6k"/><path class="ytw910bdw"/><path class="wl8ahjbfu"/><path class="lgvsn8axm"/><path class="e7pgrp-wx"/><path class="ns11or76z"/><path class="icgbjebhm"/><path class="cd_jjcbbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:success-path-duotone-thin" /></template>
<style>
.cd_jjcbbn {
  d: path("m8 12 4 4h3");
}

.e7pgrp-wx {
  d: path("M2 12h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.icgbjebhm {
  d: path("m15 13 2 2 4 -4");
}

.lgvsn8axm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 12 4 4h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ns11or76z {
  d: path("m8 12 4 -4h5");
}

.pwjia2r6k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wl8ahjbfu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 13 2 2 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ytw910bdw {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 12 4 -4h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
