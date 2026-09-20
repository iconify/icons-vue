<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mmask7b6c"/><path class="cf-dqybgk"/><path class="zm5vnrbtt"/><path class="h1_wy_9rp"/><path class="uy5j3ks5u"/><path class="ok9ioqb8x"/><path class="pl-e7wb3s"/><path class="zuzyjabxh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:skating-duotone-thin" /></template>
<style>
.cf-dqybgk {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 17h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.h1_wy_9rp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 14v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mmask7b6c {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 4v10h12v-3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ok9ioqb8x {
  d: path("M4 17h16");
}

.pl-e7wb3s {
  d: path("M6 14v3");
}

.uy5j3ks5u {
  d: path("M6 4v10h12v-3");
}

.zm5vnrbtt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 14v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zuzyjabxh {
  d: path("M18 14v3");
}

</style>
