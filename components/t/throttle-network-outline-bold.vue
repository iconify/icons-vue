<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="f1vpicczb"/><path class="o0-3vqblf"/><path class="jcxg2bbvb"/><path class="e-p0c9bfw"/><path class="jlfl_ccwj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:throttle-network-outline-bold" /></template>
<style>
.e-p0c9bfw {
  d: path("m8 3 6 6v6l-6 6");
}

.f1vpicczb {
  d: path("M2 4h8");
}

.jcxg2bbvb {
  d: path("M2 12h8");
}

.jlfl_ccwj {
  d: path("M14 12h8");
}

.o0-3vqblf {
  d: path("M2 8h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
