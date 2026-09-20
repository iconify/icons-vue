<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ia46_gbxj"/><path class="rz_vrfdnw"/><path class="nkk2t23oa"/><path class="nwh20ccjn"/><path class="d12g7vbfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:property-test-outline-bold" /></template>
<style>
.d12g7vbfa {
  d: path("m13 12 2 2 4 -4");
}

.ia46_gbxj {
  d: path("M3 6a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nkk2t23oa {
  d: path("M7.5 6 11 9.5");
}

.nwh20ccjn {
  d: path("m7.5 18 3.5 -3.5");
}

.rz_vrfdnw {
  d: path("M3 18a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
