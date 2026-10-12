<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="gl0zqx06v"/><circle class="vonm2g1wy"/><path class="f_im5073a"/><circle class="kz9qc0sgp"/><path class="m2loeebgf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-group" /></template>
<style>
.f_im5073a {
  d: path("M3.5 20.25h3a.75.75 0 0 0 .75-.75c0-2.9-1-5-2.25-5s-2.25 2.1-2.25 5a.75.75 0 0 0 .75.75m14 0h3a.75.75 0 0 0 .75-.75c0-2.9-1-5-2.25-5s-2.25 2.1-2.25 5a.75.75 0 0 0 .75.75");
}

.gl0zqx06v {
  cx: 5px;
  cy: 8.75px;
  r: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kz9qc0sgp {
  cx: 12px;
  cy: 9.75px;
  r: 2.25px;
}

.m2loeebgf {
  d: path("M10.5 20.25h3a.75.75 0 0 0 .75-.75c0-2.9-1-5-2.25-5s-2.25 2.1-2.25 5a.75.75 0 0 0 .75.75");
}

.vonm2g1wy {
  cx: 19px;
  cy: 8.75px;
  r: 2px;
}

</style>
