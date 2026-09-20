<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nfbkqjzjm"/><path class="f1orolbpb"/><path class="kh6k2u0sg"/><path class="b853q9vsx"/><path class="vxe1lob-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:price-tag-duotone-thin" /></template>
<style>
.b853q9vsx {
  d: path("M6.5 9.5v3");
}

.f1orolbpb {
  fill: currentColor;
  d: path("M14 13h5l3 3 -3 3h-5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kh6k2u0sg {
  d: path("M2 11a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.nfbkqjzjm {
  fill: currentColor;
  d: path("M2 11a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vxe1lob-r {
  d: path("M14 13h5l3 3 -3 3h-5Z");
}

</style>
