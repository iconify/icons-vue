<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="mqg2bcb3h"/><circle class="fdrwrlrfn"/><circle class="cihmkz81k"/><path class="up8g4xbvw"/><path class="t9z-_n5bj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tiara-sharp" /></template>
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

.mqg2bcb3h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.32 4.25l1.61 2.5l.32.5l-.32.5l-1.61 2.5l-.32.5l-.32-.5l-1.61-2.5l-.32-.5l.32-.5l1.61-2.5l.32-.5z");
}

.t9z-_n5bj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 15.25h.01m2.99-.5h.01m2.99.5h.01");
}

.up8g4xbvw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 19.5c2.25-4.5 5.5-7 9.25-7s7 2.5 9.25 7C18.5 18 15.25 17 12 17s-6.5 1-9.25 2.5Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
