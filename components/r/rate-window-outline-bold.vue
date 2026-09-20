<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lu1q1nb0a"/><path class="u_pwg_bmr"/><path class="lin_m3y1a"/><path class="mcqe8sbtu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rate-window-outline-bold" /></template>
<style>
.lin_m3y1a {
  d: path("M11 10.5v3");
}

.lu1q1nb0a {
  d: path("M3 10a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.mcqe8sbtu {
  d: path("M15 10.5v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u_pwg_bmr {
  d: path("M7 10.5v3");
}

</style>
