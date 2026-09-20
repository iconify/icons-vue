<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="eyx95fmam"/><path class="rkhcgsbdl"/><path class="zda0rtbri"/><path class="ao-h93max"/><path class="cdyau8b6j"/><path class="dnschyb3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:weather-week-outline-bold" /></template>
<style>
.ao-h93max {
  d: path("M9 19v3");
}

.cdyau8b6j {
  d: path("M15 19v3");
}

.dnschyb3r {
  d: path("M21 19v3");
}

.eyx95fmam {
  d: path("M4 16a4 4 0 0 1 2 -7.5A5 5 0 0 1 15.5 7a5.5 5.5 0 0 1 4.5 9Z");
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

.zda0rtbri {
  d: path("M3 19v3");
}

</style>
