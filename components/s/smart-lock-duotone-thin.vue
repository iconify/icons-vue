<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ttfv-r4jd"/><path class="i8fobbb8v"/><path class="vvghs3b3o"/><path class="eh2_kr33i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:smart-lock-duotone-thin" /></template>
<style>
.eh2_kr33i {
  d: path("M19 9q3 3 0 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i8fobbb8v {
  d: path("M6 12v8h10v-8Z");
}

.ttfv-r4jd {
  fill: currentColor;
  d: path("M6 12v8h10v-8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vvghs3b3o {
  d: path("M7 12a4 4 0 0 1 8 0");
}

</style>
