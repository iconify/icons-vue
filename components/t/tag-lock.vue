<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><path class="jdx6jwbej"/><circle class="ygzhjxbkl"/></g><rect class="ecwkvnb4e"/><path class="qxk6h6bbi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tag-lock" /></template>
<style>
.ecwkvnb4e {
  width: 5.5px;
  height: 4px;
  x: 14.75px;
  y: 17px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jdx6jwbej {
  d: path("M3.75 5.75a2 2 0 0 1 2-2h5.4a2 2 0 0 1 1.41.59l7.6 7.6a2 2 0 0 1 0 2.82l-5.43 5.43a2 2 0 0 1-2.82 0l-7.6-7.6a2 2 0 0 1-.56-1.41Z");
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

.ygzhjxbkl {
  cx: 8px;
  cy: 8px;
  r: 1.25px;
}

</style>
