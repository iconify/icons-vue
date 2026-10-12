<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><path class="b2gzvlb0a"/></g><path class="y-z1iiubr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:map-star" /></template>
<style>
.b2gzvlb0a {
  d: path("m4.4 5.75l3.45-1.5q1.15-.5 2.3-.02l3.7 1.54q1.15.48 2.3-.02l3.45-1.5q1.15-.5 1.15.75v11.5q0 1.25-1.15 1.75l-3.45 1.5q-1.15.5-2.3.02l-3.7-1.54q-1.15-.48-2.3.02l-3.45 1.5q-1.15.5-1.15-.75V7.5q0-1.25 1.15-1.75m4.6-2v14m6-11.5v14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jf0axzbmx {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y-z1iiubr {
  d: path("m17.54 13.92l.83 1.82q.15.32.49.36l2 .22q.34.04.09.28l-1.48 1.35q-.26.24-.19.58l.4 1.96q.07.35-.23.17l-1.75-.99q-.3-.17-.6 0l-1.75.99q-.3.18-.23-.17l.4-1.96q.07-.34-.19-.58l-1.48-1.35q-.25-.24.09-.28l2-.22q.34-.04.49-.36l.83-1.82q.14-.32.28 0");
}

</style>
