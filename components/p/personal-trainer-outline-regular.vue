<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aj1uncbqw"/><path class="kwvl-5zwd"/><path class="wphbr99_m"/><path class="axsqg_b2b"/><path class="yafg6v4zg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:personal-trainer-outline-regular" /></template>
<style>
.aj1uncbqw {
  d: path("M4 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.axsqg_b2b {
  d: path("M15 12h4");
}

.kwvl-5zwd {
  d: path("M2.5 16a4.5 4.5 0 0 1 9 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wphbr99_m {
  d: path("M13 10a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

.yafg6v4zg {
  d: path("M15 15h4");
}

</style>
