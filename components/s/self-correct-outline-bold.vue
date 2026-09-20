<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hxs7cr7lm"/><path class="grpcwaciz"/><path class="fy72pvbym"/><path class="bwel3nf-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:self-correct-outline-bold" /></template>
<style>
.bwel3nf-y {
  d: path("m16 15 2 2 3 -3");
}

.fy72pvbym {
  d: path("M4 16h10");
}

.grpcwaciz {
  d: path("m4 10 6 -6");
}

.hxs7cr7lm {
  d: path("M4 7h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
