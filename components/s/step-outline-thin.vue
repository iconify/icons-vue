<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tbjorldxr"/><path class="doha7k7ng"/><path class="uhg14jb-c"/><path class="xh8-ghm1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:step-outline-thin" /></template>
<style>
.doha7k7ng {
  d: path("M10 11v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tbjorldxr {
  d: path("M3 18h7");
}

.uhg14jb-c {
  d: path("M10 11h7");
}

.xh8-ghm1o {
  d: path("M17 4v7");
}

</style>
