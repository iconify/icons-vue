<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hh50h1w7h"/><path class="qxhe48bjs"/><path class="c4x33d_yv"/><path class="j-ukqcc5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tulip-outline-regular" /></template>
<style>
.c4x33d_yv {
  d: path("M5 20c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

.hh50h1w7h {
  d: path("M8 5v5l4 4 4 -4V5l-4 4Z");
}

.j-ukqcc5l {
  d: path("M13 20c0 -3.6 2.4 -6 6 -6 0 3.6 -2.4 6 -6 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qxhe48bjs {
  d: path("M12 14v7");
}

</style>
