<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cppuet5kt"/><path class="iu7kp-b7s"/><path class="d65ds0b2q"/><path class="a_97vwrqu"/><path class="t1rg4fbhf"/><path class="fhc_6lohv"/><path class="eep6j8bvo"/><path class="lvewu-bzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:step-back-duotone-thin" /></template>
<style>
.a_97vwrqu {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11 8a4 4 0 1 1 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cppuet5kt {
  fill: currentColor;
  d: path("M14 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.d65ds0b2q {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4.5 9.5 2 12l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eep6j8bvo {
  d: path("M11 8a4 4 0 1 1 4 4");
}

.fhc_6lohv {
  d: path("M4.5 9.5 2 12l2.5 2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iu7kp-b7s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 12h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lvewu-bzn {
  d: path("M14 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.t1rg4fbhf {
  d: path("M3 12h5");
}

</style>
