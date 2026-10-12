<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="nxgt63-_t"/><rect class="ej-k4rbme"/><rect class="i3bq242zg"/><path class="hqyzlvbbt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:storage-depot" /></template>
<style>
.ej-k4rbme {
  width: 8px;
  height: 7.75px;
  x: 13.25px;
  y: 13.5px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hqyzlvbbt {
  d: path("M5.5 16.25V19M8 16.25V19m8-2.75V19m2.5-2.75V19M10.75 8.25V11m2.5-2.75V11");
}

.i3bq242zg {
  width: 8px;
  height: 7.75px;
  x: 8px;
  y: 5.75px;
  rx: 1px;
}

.nxgt63-_t {
  width: 8px;
  height: 7.75px;
  x: 2.75px;
  y: 13.5px;
  rx: 1px;
}

</style>
