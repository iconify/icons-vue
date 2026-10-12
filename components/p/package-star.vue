<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><path class="uui-leb4t"/><path class="lj2ej1xdl"/></g><path class="y-z1iiubr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:package-star" /></template>
<style>
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

.lj2ej1xdl {
  d: path("m4 7.25l8 4l8-4m-8 4v9M7.75 4.75L16 9.25");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uui-leb4t {
  d: path("M20.25 7.65v8.7a1.5 1.5 0 0 1-.8 1.3l-6.55 3.4a2 2 0 0 1-1.8 0l-6.55-3.4a1.5 1.5 0 0 1-.8-1.3v-8.7a1.5 1.5 0 0 1 .8-1.3l6.55-3.4a2 2 0 0 1 1.8 0l6.55 3.4a1.5 1.5 0 0 1 .8 1.3");
}

.y-z1iiubr {
  d: path("m17.54 13.92l.83 1.82q.15.32.49.36l2 .22q.34.04.09.28l-1.48 1.35q-.26.24-.19.58l.4 1.96q.07.35-.23.17l-1.75-.99q-.3-.17-.6 0l-1.75.99q-.3.18-.23-.17l.4-1.96q.07-.34-.19-.58l-1.48-1.35q-.25-.24.09-.28l2-.22q.34-.04.49-.36l.83-1.82q.14-.32.28 0");
}

</style>
