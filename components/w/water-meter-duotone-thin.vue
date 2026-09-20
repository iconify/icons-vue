<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tu3bv3eig"/><path class="kst6m0v6a"/><path class="yoftwf7ei"/><path class="qzpg-bc7o"/><path class="ic_pehd5a"/><path class="ofzwylwbi"/><path class="ejtyvbbdg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:water-meter-duotone-thin" /></template>
<style>
.ejtyvbbdg {
  d: path("M17 15v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ic_pehd5a {
  d: path("M3 17h18");
}

.kst6m0v6a {
  fill: currentColor;
  d: path("m12 6 2 2a2.8 2.8 0 1 1 -4 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ofzwylwbi {
  d: path("M7 15v4");
}

.qzpg-bc7o {
  d: path("m12 6 2 2a2.8 2.8 0 1 1 -4 0Z");
}

.tu3bv3eig {
  fill: currentColor;
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yoftwf7ei {
  d: path("M6 9a6 6 0 1 0 12 0A6 6 0 1 0 6 9");
}

</style>
