<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p-98pibqi"/><path class="uchchabsk"/><path class="aeyekmbly"/><path class="ly1pbttmf"/><path class="pkgnr07qg"/><path class="c47gbhbtk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:school-trip-outline-regular" /></template>
<style>
.aeyekmbly {
  d: path("M3 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.c47gbhbtk {
  d: path("m20 6 -4 4h4Z");
}

.ly1pbttmf {
  d: path("M11 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p-98pibqi {
  d: path("M2 8a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.pkgnr07qg {
  d: path("M20 20V10");
}

.uchchabsk {
  d: path("M2 10h14");
}

</style>
