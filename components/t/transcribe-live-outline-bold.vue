<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k6nj2fbya"/><path class="x50q_4bdr"/><path class="vwjk1ok-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:transcribe-live-outline-bold" /></template>
<style>
.k6nj2fbya {
  d: path("M3 5h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vwjk1ok-c {
  d: path("M3 17h4l2.5 -2.5L12 17l2.5 -2.5L17 17h4");
}

.x50q_4bdr {
  d: path("M3 10h18");
}

</style>
