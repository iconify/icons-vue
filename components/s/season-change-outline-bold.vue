<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="phjqq0bfl"/><path class="pyq-q6b7b"/><path class="g45hqpb0s"/><path class="l90ci7bpu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:season-change-outline-bold" /></template>
<style>
.g45hqpb0s {
  d: path("M10.5 12h3");
}

.l90ci7bpu {
  d: path("m12 9.5 2.5 2.5 -2.5 2.5");
}

.phjqq0bfl {
  d: path("M2 16c0 -4.8 3.2 -8 8 -8 0 4.8 -3.2 8 -8 8");
}

.pyq-q6b7b {
  d: path("M18 8v8m-4 0 8 -8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
