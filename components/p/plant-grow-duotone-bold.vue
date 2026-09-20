<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hhl3fcb6i"/><path class="qeqqdxnkb"/><path class="ler50rfbf"/><path class="b-i6_ubyt"/><path class="uerippblb"/><path class="i4kf51esh"/><path class="iwg_dsj0c"/><path class="m0f5ny81l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:plant-grow-duotone-bold" /></template>
<style>
.b-i6_ubyt {
  d: path("M3 14c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

.hhl3fcb6i {
  fill: currentColor;
  d: path("M3 14c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.i4kf51esh {
  d: path("M19 5v14");
}

.iwg_dsj0c {
  d: path("M16.5 7.5 19 5l2.5 2.5");
}

.ler50rfbf {
  d: path("M9 8v12");
}

.m0f5ny81l {
  d: path("M5 20h8");
}

.qeqqdxnkb {
  fill: currentColor;
  d: path("M10 11c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uerippblb {
  d: path("M10 11c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

</style>
