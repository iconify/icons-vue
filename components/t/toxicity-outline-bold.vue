<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="hol5d7bwd"/><path class="d46lplb8g"/><path class="nmuh1-bte"/><path class="spa1l0bcs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:toxicity-outline-bold" /></template>
<style>
.d46lplb8g {
  d: path("M7 16v5l5 -5");
}

.hol5d7bwd {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.nmuh1-bte {
  d: path("m9 7 6 6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.spa1l0bcs {
  d: path("m15 7 -6 6");
}

</style>
