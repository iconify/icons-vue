<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fi8vse7ag"/><path class="yopbfmbxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:soldering-iron" /></template>
<style>
.fi8vse7ag {
  d: path("m12.75 8.26l.55.54q1.59 1.59 0 3.18l-2.79 2.79q-1.59 1.59-3.18 0l-.55-.55q-1.59-1.59 0-3.18l2.79-2.78q1.59-1.59 3.18 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yopbfmbxn {
  d: path("m12.09 7.6l2.99-2.99l3.73-1.86l-1.87 3.73l-2.98 2.98Zm-5.03 6.9l-.75.74a2.11 2.11 0 0 0 0 2.98l2.24 2.24");
}

</style>
