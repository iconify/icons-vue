<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z3eyrdd0c"/><path class="u6ckfiv0g"/><path class="hfg-g6b7u"/><path class="e7q8l6x6g"/><path class="esqrnvsht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:precision-outline-thin" /></template>
<style>
.e7q8l6x6g {
  d: path("M6 14h5");
}

.esqrnvsht {
  d: path("M6 18h7.5");
}

.hfg-g6b7u {
  d: path("M6 10h7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.u6ckfiv0g {
  d: path("M6 6h5");
}

.z3eyrdd0c {
  d: path("M6 4a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

</style>
