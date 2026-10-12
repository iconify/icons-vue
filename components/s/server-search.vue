<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="y9tr6bcfx"><g mask="url(#SVGsZ1vtcCp)"><rect class="xd_lnabfh"/><rect class="yc80kqblr"/><path class="qwn4--teq"/><path class="va-cqqbhp"/></g><path class="m-fq38bof"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:server-search" /></template>
<style>
.jf0axzbmx {
  cx: 17.5px;
  cy: 17.5px;
  r: 6px;
}

.m-fq38bof {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.25 16.75a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m4.5 2L20 20");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qwn4--teq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.25 7h.01m-.01 10h.01");
}

.va-cqqbhp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.25 7h5.5m-5.5 10h5.5");
}

.xd_lnabfh {
  width: 17.5px;
  height: 7.5px;
  x: 3.25px;
  y: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yc80kqblr {
  width: 17.5px;
  height: 7.5px;
  x: 3.25px;
  y: 13.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2px;
}

</style>
