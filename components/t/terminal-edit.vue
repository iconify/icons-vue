<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><rect class="fr9wc8ere"/><path class="nc0is4brm"/></g><path class="uaginbcio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:terminal-edit" /></template>
<style>
.fr9wc8ere {
  width: 18.5px;
  height: 16.5px;
  x: 2.75px;
  y: 3.75px;
  rx: 2.5px;
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

.nc0is4brm {
  d: path("m7.25 9.25l3 2.75l-3 2.75");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uaginbcio {
  d: path("m15.25 19.75l.5-2.25l2.5-2.5A1.24 1.24 0 0 1 20 16.75l-2.5 2.5Zm1-2.75L18 18.75");
}

</style>
