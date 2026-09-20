<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dktry7bqc"/><path class="i-o0whboy"/><path class="a-bh3zwuf"/><path class="w7_ovbzxo"/><path class="t0kgu-35p"/><path class="bo51iypxr"/><path class="xz82qebme"/><path class="lz9b4vtgl"/><path class="glv5tabri"/><path class="x-fkne0xd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:typhoon-duotone-bold" /></template>
<style>
.a-bh3zwuf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 12a7 7 0 0 1 14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bo51iypxr {
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.dktry7bqc {
  fill: currentColor;
  d: path("M10 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.glv5tabri {
  d: path("M19 12V5");
}

.i-o0whboy {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 12a7 7 0 0 1 -14 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lz9b4vtgl {
  d: path("M5 12a7 7 0 0 1 14 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t0kgu-35p {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w7_ovbzxo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 12V5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x-fkne0xd {
  d: path("M5 12v7");
}

.xz82qebme {
  d: path("M19 12a7 7 0 0 1 -14 0");
}

</style>
