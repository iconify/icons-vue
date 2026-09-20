<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c5icmybsm"/><path class="zhn_01m4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:release-candidate-outline-thin" /></template>
<style>
.c5icmybsm {
  d: path("m4 12 6 -6h10v12H10Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zhn_01m4j {
  d: path("m14 9.5 2.5 2.5 -2.5 2.5 -2.5 -2.5Z");
}

</style>
