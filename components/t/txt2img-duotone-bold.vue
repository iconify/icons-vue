<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aknqtcczd"/><path class="f1vpicczb"/><path class="o0-3vqblf"/><path class="gyvfay9gb"/><path class="rns28-8pl"/><path class="kkozh6bab"/><path class="e46qmbbbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:txt2img-duotone-bold" /></template>
<style>
.aknqtcczd {
  fill: currentColor;
  d: path("M11 13a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2h-7a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.e46qmbbbk {
  d: path("m14 19 2.5 -2.5L19 19");
}

.f1vpicczb {
  d: path("M2 4h8");
}

.gyvfay9gb {
  d: path("m4 12 4 4");
}

.kkozh6bab {
  d: path("M11 13a2 2 0 0 1 2 -2h7a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2h-7a2 2 0 0 1 -2 -2Z");
}

.o0-3vqblf {
  d: path("M2 8h8");
}

.rns28-8pl {
  d: path("M8 12.5V16H4.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
