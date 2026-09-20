<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c8e13sbqx"/><path class="jkh8z5-ob"/><path class="d-ycm7dex"/><path class="tw1khnbtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quantize-4bit-duotone-thin" /></template>
<style>
.c8e13sbqx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m3 9 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d-ycm7dex {
  d: path("m3 9 6 -6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jkh8z5-ob {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21h5v-5h5v-5h5V6h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tw1khnbtv {
  d: path("M3 21h5v-5h5v-5h5V6h3");
}

</style>
