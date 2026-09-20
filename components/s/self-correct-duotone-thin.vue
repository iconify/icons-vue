<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x3tbdc0ds"/><path class="aovd5aczi"/><path class="f0o3rybpq"/><path class="q983g6b5m"/><path class="hxs7cr7lm"/><path class="grpcwaciz"/><path class="fy72pvbym"/><path class="bwel3nf-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:self-correct-duotone-thin" /></template>
<style>
.aovd5aczi {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m4 10 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bwel3nf-y {
  d: path("m16 15 2 2 3 -3");
}

.f0o3rybpq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 16h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fy72pvbym {
  d: path("M4 16h10");
}

.grpcwaciz {
  d: path("m4 10 6 -6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hxs7cr7lm {
  d: path("M4 7h10");
}

.q983g6b5m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m16 15 2 2 3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x3tbdc0ds {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 7h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
