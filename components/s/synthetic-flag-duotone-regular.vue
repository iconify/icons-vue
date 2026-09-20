<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t7edyg0pd"/><path class="llbhzb2kh"/><path class="g49_wlc2j"/><path class="jowgr_bsw"/><path class="dixqoybsq"/><path class="medja4cva"/><path class="ndddypvah"/><path class="qot4e3zhe"/><path class="qhkmcqbdq"/><path class="xhkxitbia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:synthetic-flag-duotone-regular" /></template>
<style>
.dixqoybsq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 5h3v3H5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g49_wlc2j {
  fill: currentColor;
  d: path("M18 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jowgr_bsw {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 4v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.llbhzb2kh {
  fill: currentColor;
  d: path("M13 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.medja4cva {
  d: path("M5 4v12");
}

.ndddypvah {
  d: path("M5 5h3v3H5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qhkmcqbdq {
  d: path("M13 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.qot4e3zhe {
  d: path("M8 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.t7edyg0pd {
  fill: currentColor;
  d: path("M8 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xhkxitbia {
  d: path("M18 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
