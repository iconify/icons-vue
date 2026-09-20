<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yngda3bvc"/><path class="x1_r36phd"/><path class="rrzohjbez"/><path class="gstzuxb9r"/><path class="wggowmhtc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rowing-machine-outline-bold" /></template>
<style>
.gstzuxb9r {
  d: path("M5 7v4");
}

.rrzohjbez {
  d: path("M12 12v3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wggowmhtc {
  d: path("M5 9h4");
}

.x1_r36phd {
  d: path("M9 12h6");
}

.yngda3bvc {
  d: path("M3 15h18");
}

</style>
