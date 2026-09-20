<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q5_980zya"/><path class="t12-ippwj"/><path class="jcj1h_mmu"/><path class="wzdwamk1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:self-join-duotone-bold" /></template>
<style>
.jcj1h_mmu {
  d: path("M4.5 10.26a8 8 0 0 1 15.04 0");
}

.q5_980zya {
  fill: currentColor;
  d: path("M7 13a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
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

.t12-ippwj {
  d: path("M7 13a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.wzdwamk1s {
  d: path("M17 6h3v3");
}

</style>
