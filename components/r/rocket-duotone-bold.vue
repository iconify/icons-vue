<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tvy4b7bnk"/><path class="bkhpo871l"/><path class="g7g9z5bnc"/><path class="zesrtccnv"/><path class="sc1yd0n6y"/><path class="c3v-iswgv"/><path class="qrqk-5btd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rocket-duotone-bold" /></template>
<style>
.bkhpo871l {
  fill: currentColor;
  d: path("M10 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.c3v-iswgv {
  d: path("m16 12 5 5h-5");
}

.g7g9z5bnc {
  d: path("m12 2 4 4v11H8V6Z");
}

.qrqk-5btd {
  d: path("m9 17 3 3 3 -3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sc1yd0n6y {
  d: path("m8 12 -5 5h5");
}

.tvy4b7bnk {
  fill: currentColor;
  d: path("m12 2 4 4v11H8V6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zesrtccnv {
  d: path("M10 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
