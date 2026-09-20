<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ugdbidcqi"/><path class="bb_62lblh"/><path class="at7ws5bbl"/><path class="okqksmbze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mtbf-outline-regular" /></template>
<style>
.at7ws5bbl {
  d: path("M9.5 12h5");
}

.bb_62lblh {
  d: path("M5.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.okqksmbze {
  d: path("M14.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ugdbidcqi {
  d: path("M16.23 2.94a10 10 0 1 1 -8.46 0");
}

</style>
