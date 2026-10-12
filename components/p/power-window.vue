<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h5el8ebvj"/><path class="v8pwi-q0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:power-window" /></template>
<style>
.h5el8ebvj {
  d: path("m4.08 9.51l3.34-3.77q1.33-1.49 3.33-1.49h1.5q2 0 2 2v12q0 2-2 2h-7.5q-2 0-2-2V13q0-2 1.33-3.49");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v8pwi-q0s {
  d: path("m6.25 11l3.5-3.75h1.75V11Zm13-6.25v14.5m-2-12.5l2-2l2 2m-4 10.5l2 2l2-2");
}

</style>
