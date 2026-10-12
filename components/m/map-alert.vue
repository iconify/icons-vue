<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="y9tr6bcfx"><g mask="url(#SVGsZ1vtcCp)" class="nl157099w"><path class="b2gzvlb0a"/></g><path class="yr-noebov"/><path class="fxu54sbac"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:map-alert" /></template>
<style>
.b2gzvlb0a {
  d: path("m4.4 5.75l3.45-1.5q1.15-.5 2.3-.02l3.7 1.54q1.15.48 2.3-.02l3.45-1.5q1.15-.5 1.15.75v11.5q0 1.25-1.15 1.75l-3.45 1.5q-1.15.5-2.3.02l-3.7-1.54q-1.15-.48-2.3.02l-3.45 1.5q-1.15.5-1.15-.75V7.5q0-1.25 1.15-1.75m4.6-2v14m6-11.5v14");
}

.fxu54sbac {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.5 20.25h.01");
}

.jf0axzbmx {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

.nl157099w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yr-noebov {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.5 14.5v3.25");
}

</style>
