<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="agpw-tbwq"/><path class="b51mjibkt"/><path class="kjjsomb8f"/><path class="p3zi2gbag"/><path class="na65nl0eo"/><path class="cs3crkb9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:static-stability-duotone-bold" /></template>
<style>
.agpw-tbwq {
  fill: currentColor;
  d: path("M8 10a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.b51mjibkt {
  d: path("M8 10a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.cs3crkb9d {
  d: path("m13.5 18 -2 2 2 2");
}

.kjjsomb8f {
  d: path("M3 4h7.5");
}

.na65nl0eo {
  d: path("M13.5 20H21");
}

.p3zi2gbag {
  d: path("m10.5 2 2 2 -2 2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
