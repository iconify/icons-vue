<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ymp2b4b6u"/><path class="jx89umbuc"/><path class="zr0lwnjnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:output-encoding-outline-regular" /></template>
<style>
.jx89umbuc {
  d: path("M9.5 8.5 7 11l2.5 2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ymp2b4b6u {
  d: path("M15 5h5v8l-8 8 -8 -8V5h5");
}

.zr0lwnjnt {
  d: path("M14.5 8.5 17 11l-2.5 2.5");
}

</style>
