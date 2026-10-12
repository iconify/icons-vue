<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="muw6_18xf"/><path class="b9ekzkbie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:road-sign" /></template>
<style>
.b9ekzkbie {
  d: path("M10 12.5v-1.75a1.25 1.25 0 0 1 1.25-1.25h3.25M13 7.75l1.75 1.75L13 11.25m-1 6v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.muw6_18xf {
  d: path("m13.06 3.81l5.13 5.13q1.06 1.06 0 2.12l-5.13 5.13q-1.06 1.06-2.12 0l-5.13-5.13q-1.06-1.06 0-2.12l5.13-5.13q1.06-1.06 2.12 0");
}

</style>
