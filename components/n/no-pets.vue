<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="mwo2o7bby"/><path class="yreu97ylk"/><path class="s_5nglnaj"/><path class="ucws8vbwy"/><path class="qsm8r14by"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:no-pets" /></template>
<style>
.mwo2o7bby {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 18a2.5 2 0 1 0 5 0a2.5 2 0 1 0-5 0");
}

.qsm8r14by {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.75 3.75l16.5 16.5");
}

.s_5nglnaj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.5 8a2.5 2 0 1 0 5 0a2.5 2 0 1 0-5 0");
}

.ucws8vbwy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 4.75h.01m2.74-1.5h.01m2.74 1h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yreu97ylk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 14.75h.01m2.74-1.5h.01m2.74 1h.01");
}

</style>
