<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xa771-t-o"/><path class="zxt5gfb3l"/><path class="ugdbidcqi"/><path class="m_ko-gb4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:world-model-duotone-regular" /></template>
<style>
.m_ko-gb4s {
  d: path("m8 15 4 -4 4 4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ugdbidcqi {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

.xa771-t-o {
  fill: currentColor;
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zxt5gfb3l {
  fill: currentColor;
  d: path("m8 15 4 -4 4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
