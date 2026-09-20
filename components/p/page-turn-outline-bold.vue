<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="kn-4tic2i"/><path class="t8qnl-bvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:page-turn-outline-bold" /></template>
<style>
.kn-4tic2i {
  d: path("M4 21V3h10l6 6v12Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t8qnl-bvo {
  d: path("M14 3v6h6");
}

</style>
