<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q1lsee9xq"/><path class="emo-jf0pj"/><path class="diaqyhfcp"/><path class="a97qfmbix"/><path class="pohupsbfv"/><path class="f99n1fbkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vet-outline-regular" /></template>
<style>
.a97qfmbix {
  d: path("M14 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.diaqyhfcp {
  d: path("M10 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.emo-jf0pj {
  d: path("M6 9a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.f99n1fbkg {
  d: path("M16 7h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pohupsbfv {
  d: path("M19 4v6");
}

.q1lsee9xq {
  d: path("M11 19c-2.5 0 -4.5 -2 -4.5 -4s2 -3.5 4.5 -3.5 4.5 1.5 4.5 3.5 -2 4 -4.5 4");
}

</style>
