<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tlah7acnn"/><path class="elo_ccj2r"/><path class="yz_nd208h"/><path class="htl7tccnk"/><path class="zs2zs3b-j"/><path class="y0v87rbkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tool-chain-outline-regular" /></template>
<style>
.elo_ccj2r {
  d: path("M9 4v7");
}

.htl7tccnk {
  d: path("M8 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tlah7acnn {
  d: path("M6 13a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

.y0v87rbkg {
  d: path("M14 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.yz_nd208h {
  d: path("M15 4v7");
}

.zs2zs3b-j {
  d: path("M10.5 15.5h3");
}

</style>
