<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="fli2w14co"/><path class="tczno9b3c"/><path class="x26a8iq1c"/><path class="bq0_6ubvh"/><path class="bsqy413qs"/><path class="ds7-fpf_b"/><path class="tz91nhk-p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:parent-meeting-duotone-bold" /></template>
<style>
.bq0_6ubvh {
  d: path("M2 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.bsqy413qs {
  d: path("M16 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.ds7-fpf_b {
  d: path("M3 20v-5h4v5");
}

.fli2w14co {
  fill: currentColor;
  d: path("M2 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tczno9b3c {
  fill: currentColor;
  d: path("M16 6a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.tz91nhk-p {
  d: path("M17 20v-5h4v5");
}

.x26a8iq1c {
  d: path("M2 12h20");
}

</style>
