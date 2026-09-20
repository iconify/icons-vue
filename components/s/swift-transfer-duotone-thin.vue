<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yw0x1wbxg"/><path class="x1ltxj_da"/><path class="mcubrkb2y"/><path class="znp96bc9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:swift-transfer-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mcubrkb2y {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

.x1ltxj_da {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 12 -3 3h2.5l-3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yw0x1wbxg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.znp96bc9s {
  d: path("m15 12 -3 3h2.5l-3 3");
}

</style>
