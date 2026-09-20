<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lko_r07tc"/><path class="e7pgrp-wx"/><path class="jtj73ab7i"/><path class="q6c5h5b2r"/><path class="rv19xcoye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:memory-consolidate-outline-regular" /></template>
<style>
.e7pgrp-wx {
  d: path("M2 12h6");
}

.jtj73ab7i {
  d: path("M2 17h6");
}

.lko_r07tc {
  d: path("M2 7h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q6c5h5b2r {
  d: path("m10 9.5 2.5 2.5 -2.5 2.5");
}

.rv19xcoye {
  d: path("M15.5 12a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2 2 2 0 0 1 -2 2h-2.5a2 2 0 0 1 -2 -2");
}

</style>
