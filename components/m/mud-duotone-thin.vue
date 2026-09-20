<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rtfsd-fjl"/><path class="emj1pbzvk"/><path class="avyvkw01i"/><path class="u3pvd_qut"/><path class="i6tuq5bxi"/><path class="zfnkrabzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mud-duotone-thin" /></template>
<style>
.avyvkw01i {
  fill: currentColor;
  d: path("M14 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.emj1pbzvk {
  fill: currentColor;
  d: path("M7 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
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

.i6tuq5bxi {
  d: path("M7 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.rtfsd-fjl {
  fill: currentColor;
  d: path("M2 16a4 4 0 0 1 6 -2 5 5 0 0 1 8 -1 4 4 0 0 1 6 3v4H2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.u3pvd_qut {
  d: path("M2 16a4 4 0 0 1 6 -2 5 5 0 0 1 8 -1 4 4 0 0 1 6 3v4H2Z");
}

.zfnkrabzj {
  d: path("M14 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
