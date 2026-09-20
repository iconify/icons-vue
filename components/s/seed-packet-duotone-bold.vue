<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g6iop94az"/><path class="e04igbcxt"/><path class="uvugsybla"/><path class="d7j29trjs"/><path class="f8gsx7b5s"/><path class="p-3tqnbzb"/><path class="ak_t1bcfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:seed-packet-duotone-bold" /></template>
<style>
.ak_t1bcfw {
  d: path("M14 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.d7j29trjs {
  d: path("M6 4h12v16H6Z");
}

.e04igbcxt {
  fill: currentColor;
  d: path("M9 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.f8gsx7b5s {
  d: path("M6 8h12");
}

.g6iop94az {
  fill: currentColor;
  d: path("M6 4h12v16H6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.p-3tqnbzb {
  d: path("M9 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uvugsybla {
  fill: currentColor;
  d: path("M14 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
