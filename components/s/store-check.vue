<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<mask id="SVGsZ1vtcCp" width="24" height="24" x="0" y="0" maskUnits="userSpaceOnUse"><path class="py7ktqbvf"/><circle class="jf0axzbmx"/></mask><g class="hntgybcog"><g mask="url(#SVGsZ1vtcCp)"><path class="me4vljbbp"/></g><path class="beqvkx5mb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:store-check" /></template>
<style>
.beqvkx5mb {
  d: path("m14.75 17.75l1.75 1.75l3.5-3.75");
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

.me4vljbbp {
  d: path("M5.4 3.25h13.2a1.5 1.5 0 0 1 1.4.97l1.25 3.28v.75a2.5 2.5 0 0 1-2.5 2.5H5.25a2.5 2.5 0 0 1-2.5-2.5V7.5L4 4.22a1.5 1.5 0 0 1 1.4-.97m3.85 0l-.5 7.5m6-7.5l.5 7.5m-10.5 2.5h14.5v6a2 2 0 0 1-2 2H6.75a2 2 0 0 1-2-2Z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
