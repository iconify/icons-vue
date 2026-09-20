<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w2ed1xbxm"/><path class="p39ktbcba"/><path class="q5rc7xb2g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-fast-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p39ktbcba {
  d: path("m7 8 4 4 -4 4 -4 -4Z");
}

.q5rc7xb2g {
  d: path("m20 6 -5 5h4l-5 5");
}

.w2ed1xbxm {
  fill: currentColor;
  d: path("m7 8 4 4 -4 4 -4 -4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
