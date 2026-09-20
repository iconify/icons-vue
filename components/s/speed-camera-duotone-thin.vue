<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="suza7jhjj"/><path class="pjgjnzbhx"/><path class="emda2p1-f"/><path class="ik6mh31gy"/><path class="f9z-0kbvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:speed-camera-duotone-thin" /></template>
<style>
.emda2p1-f {
  d: path("M18 7h3v5h-3");
}

.f9z-0kbvx {
  d: path("M6 21h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ik6mh31gy {
  d: path("M11 14v7");
}

.pjgjnzbhx {
  d: path("M4 7a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.suza7jhjj {
  fill: currentColor;
  d: path("M4 7a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
