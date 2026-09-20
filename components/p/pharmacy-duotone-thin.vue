<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l2wdis8zs"/><path class="o77mms0ex"/><path class="vr9ht74fa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pharmacy-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l2wdis8zs {
  fill: currentColor;
  d: path("M3 11h18a9 9 0 0 1 -18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.o77mms0ex {
  d: path("M3 11h18a9 9 0 0 1 -18 0");
}

.vr9ht74fa {
  d: path("m8 3 7 7");
}

</style>
