<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><path class="d4ss5kb_g"/><path class="epjz5kbpd"/></g><rect class="ecwkvnb4e"/><path class="qxk6h6bbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trophy-lock" /></template>
<style>
.d4ss5kb_g {
  d: path("M6.75 3.25h10.5v5.5a5.25 5.25 0 0 1-10.5 0Z");
}

.ecwkvnb4e {
  width: 5.5px;
  height: 4px;
  x: 14.75px;
  y: 17px;
  rx: 1px;
}

.epjz5kbpd {
  d: path("M6.75 5.25h-1.5a2 2 0 0 0-2 2c0 2.25 1.75 3.75 4.25 4m9.75-6h1.5a2 2 0 0 1 2 2c0 2.25-1.75 3.75-4.25 4");
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

.qxk6h6bbi {
  d: path("M16 17v-1a1.5 1.5 0 0 1 3 0v1");
}

</style>
