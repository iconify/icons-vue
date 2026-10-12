<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="na8rwp2fd"/><rect class="qjq27q61i"/><path class="s7hdf8bld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tv-and-box" /></template>
<style>
.na8rwp2fd {
  width: 18.5px;
  height: 11.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.qjq27q61i {
  width: 11.5px;
  height: 4px;
  x: 6.25px;
  y: 17.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

.s7hdf8bld {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.75 19.25h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
