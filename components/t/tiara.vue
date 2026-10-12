<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="uvn-uwbls"/><circle class="fdrwrlrfn"/><circle class="cihmkz81k"/><path class="uj3kycbof"/><path class="t9z-_n5bj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tiara" /></template>
<style>
.cihmkz81k {
  cx: 17.25px;
  cy: 11.75px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.fdrwrlrfn {
  cx: 6.75px;
  cy: 11.75px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t9z-_n5bj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 15.25h.01m2.99-.5h.01m2.99.5h.01");
}

.uj3kycbof {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 19.5c2.25-4.5 5.5-7 9.25-7s7 2.5 9.25 7C18.5 18 15.25 17 12 17s-6.5 1-9.25 2.5");
}

.uvn-uwbls {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.32 4.25l1.61 2.5q.32.5 0 1l-1.61 2.5q-.32.5-.64 0l-1.61-2.5q-.32-.5 0-1l1.61-2.5q.32-.5.64 0");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
