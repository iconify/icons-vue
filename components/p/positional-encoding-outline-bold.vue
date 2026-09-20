<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ynq2074_v"/><path class="tip34zbqw"/><path class="aam38ubkv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:positional-encoding-outline-bold" /></template>
<style>
.aam38ubkv {
  d: path("M14 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tip34zbqw {
  d: path("M6 7a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ynq2074_v {
  d: path("m3 16 4 -4 4 4 4 -4 4 4");
}

</style>
