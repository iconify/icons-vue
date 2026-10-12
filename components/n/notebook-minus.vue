<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><rect class="tbuwkfblz"/><path class="ekfvqi6-x"/></g><path class="notrppkqh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:notebook-minus" /></template>
<style>
.ekfvqi6-x {
  d: path("M3.75 7.25h3.5M3.75 12h3.5m-3.5 4.75h3.5m3.75-9h4.5");
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

.notrppkqh {
  d: path("M14.75 17.5h5.5");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tbuwkfblz {
  width: 13.5px;
  height: 18.5px;
  x: 5.75px;
  y: 2.75px;
  rx: 2.5px;
}

</style>
