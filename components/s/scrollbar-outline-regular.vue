<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="viv5gg8xx"/><path class="ze8z1jbtg"/><path class="eczutjtvu"/><path class="p3-3c1i1b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:scrollbar-outline-regular" /></template>
<style>
.eczutjtvu {
  d: path("M5 13h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p3-3c1i1b {
  d: path("M19 5v7");
}

.viv5gg8xx {
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.ze8z1jbtg {
  d: path("M5 8h10");
}

</style>
