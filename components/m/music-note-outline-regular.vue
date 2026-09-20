<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ew7y79byi"/><path class="huj3g_bus"/><path class="xob7qnbfo"/><path class="nycbsrkgh"/><path class="wwbyt5bkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:music-note-outline-regular" /></template>
<style>
.ew7y79byi {
  d: path("M5 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.huj3g_bus {
  d: path("M13 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nycbsrkgh {
  d: path("M17 17V5");
}

.wwbyt5bkd {
  d: path("M9 5h8");
}

.xob7qnbfo {
  d: path("M9 17V5");
}

</style>
