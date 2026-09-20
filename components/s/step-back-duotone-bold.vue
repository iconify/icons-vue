<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="cppuet5kt"/><path class="hfbgrrm0x"/><path class="rzbih8blw"/><path class="t-ccjubee"/><path class="t1rg4fbhf"/><path class="fhc_6lohv"/><path class="eep6j8bvo"/><path class="lvewu-bzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:step-back-duotone-bold" /></template>
<style>
.cppuet5kt {
  fill: currentColor;
  d: path("M14 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.eep6j8bvo {
  d: path("M11 8a4 4 0 1 1 4 4");
}

.fhc_6lohv {
  d: path("M4.5 9.5 2 12l2.5 2.5");
}

.hfbgrrm0x {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lvewu-bzn {
  d: path("M14 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.rzbih8blw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4.5 9.5 2 12l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t-ccjubee {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 8a4 4 0 1 1 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t1rg4fbhf {
  d: path("M3 12h5");
}

</style>
