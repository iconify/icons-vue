<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r3faxubne"/><path class="ws1d0fbts"/><path class="f3zridcmg"/><path class="z_c7updjp"/><path class="m0msdy1bm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:river-level-outline-thin" /></template>
<style>
.f3zridcmg {
  d: path("m3 14 2.5 -2.5L8 14l2.5 -2.5L13 14l2.5 -2.5L18 14l2.5 -2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m0msdy1bm {
  d: path("M5 11h4");
}

.r3faxubne {
  d: path("M4 4v16");
}

.ws1d0fbts {
  d: path("M20 4v16");
}

.z_c7updjp {
  d: path("M5 8h4");
}

</style>
