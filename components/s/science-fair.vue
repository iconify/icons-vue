<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="v7wzdbcyk"/><path class="bpem9blhc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:science-fair" /></template>
<style>
.bpem9blhc {
  d: path("m6.75 5.75l-3.1 1.2a1.25 1.25 0 0 0-.9 1.2v7.6a1.25 1.25 0 0 0 1.05 1.23l2.95.77m10.5-12l3.1 1.2a1.25 1.25 0 0 1 .9 1.2v7.6a1.25 1.25 0 0 1-1.05 1.23l-2.95.77M11.25 7h1.5v2.75l1.75 3.5a1 1 0 0 1-.9 1.45h-3.2a1 1 0 0 1-.9-1.45l1.75-3.5Zm-8.5 14h18.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7wzdbcyk {
  width: 10.5px;
  height: 14px;
  x: 6.75px;
  y: 3.75px;
  rx: 1.5px;
}

</style>
