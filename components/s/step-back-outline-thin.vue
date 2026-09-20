<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t1rg4fbhf"/><path class="fhc_6lohv"/><path class="eep6j8bvo"/><path class="lvewu-bzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:step-back-outline-thin" /></template>
<style>
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

.lvewu-bzn {
  d: path("M14 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.t1rg4fbhf {
  d: path("M3 12h5");
}

</style>
