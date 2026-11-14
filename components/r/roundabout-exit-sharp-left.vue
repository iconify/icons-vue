<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fhdmpm8re"/><path class="gnxbd7fhv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:roundabout-exit-sharp-left" /></template>
<style>
.fhdmpm8re {
  d: path("M13.25 21.5v-7a5 5 0 1 0-3.5-1.5l-4 4");
}

.gnxbd7fhv {
  d: path("M9 17H5.75v-3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
