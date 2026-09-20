<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="exx4qg62z"/><path class="o8od38cnm"/><path class="z5iv6lbtc"/><path class="xaedo1bnv"/><path class="omq19fbzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sunset-header-outline-bold" /></template>
<style>
.exx4qg62z {
  d: path("M7 15a5 5 0 0 1 10 0");
}

.o8od38cnm {
  d: path("M4 18h16");
}

.omq19fbzw {
  d: path("m19 8 -2 2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xaedo1bnv {
  d: path("m5 8 2 2");
}

.z5iv6lbtc {
  d: path("M12 4.5V7");
}

</style>
