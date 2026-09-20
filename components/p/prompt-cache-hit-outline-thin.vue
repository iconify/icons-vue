<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b4x_isbqv"/><path class="d_6ujebpi"/><path class="c5gaambbs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:prompt-cache-hit-outline-thin" /></template>
<style>
.b4x_isbqv {
  d: path("M8 6H5v12h3");
}

.c5gaambbs {
  d: path("M13.5 9.5 11 12h2.5L11 14.5");
}

.d_6ujebpi {
  d: path("M16 6h3v12h-3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
