<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c9mcwl4zs"/><path class="iren7cb1n"/><path class="a2npm1ulw"/><path class="m2wceccgo"/><path class="aslbbf-5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rotary-table" /></template>
<style>
.a2npm1ulw {
  fill: currentColor;
  d: path("m12.756 11.191l.744.434a1.013 1.013 0 0 1 0 1.75l-.744.434a1.5 1.5 0 0 1-1.512 0l-.744-.434a1.013 1.013 0 0 1 0-1.75l.744-.434a1.5 1.5 0 0 1 1.512 0");
}

.aslbbf-5x {
  d: path("M15.75 4.75h2.75V2");
}

.c9mcwl4zs {
  d: path("M2.5 12.5a9.5 4.5 0 1 0 19 0a9.5 4.5 0 1 0-19 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iren7cb1n {
  d: path("M2.5 12.5V16a9.5 4.5 0 0 0 19 0v-3.5");
}

.m2wceccgo {
  d: path("M3.5 7a10 9.5 0 0 1 15-2.25");
}

</style>
