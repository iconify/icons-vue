<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="t0jrdmbrp"/><rect class="h818b6a5x"/><rect class="w7u0-7lvs"/><rect class="h12vrdf2z"/><rect class="kgi2f4b0m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:waffle" /></template>
<style>
.h12vrdf2z {
  width: 4px;
  height: 4px;
  x: 6.25px;
  y: 13.75px;
  rx: 1px;
}

.h818b6a5x {
  width: 4px;
  height: 4px;
  x: 6.25px;
  y: 6.25px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kgi2f4b0m {
  width: 4px;
  height: 4px;
  x: 13.75px;
  y: 13.75px;
  rx: 1px;
}

.t0jrdmbrp {
  width: 17.5px;
  height: 17.5px;
  x: 3.25px;
  y: 3.25px;
  rx: 4px;
}

.w7u0-7lvs {
  width: 4px;
  height: 4px;
  x: 13.75px;
  y: 6.25px;
  rx: 1px;
}

</style>
