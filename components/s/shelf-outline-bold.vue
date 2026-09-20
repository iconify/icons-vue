<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ozi-k-boi"/><path class="n-7t0yb1r"/><path class="rkhcgsbdl"/><path class="vxuzbkitn"/><path class="z1zyir08z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:shelf-outline-bold" /></template>
<style>
.n-7t0yb1r {
  d: path("M3 13h18");
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vxuzbkitn {
  d: path("M5.5 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.z1zyir08z {
  d: path("M14.5 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
