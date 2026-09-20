<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ehzfylb8o"/><path class="nj8530sxr"/><path class="okud9xj_d"/><path class="kpt6n0b9i"/><path class="f4ily5bwp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:quiz-duotone-regular" /></template>
<style>
.ehzfylb8o {
  fill: currentColor;
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.f4ily5bwp {
  d: path("M10.5 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.kpt6n0b9i {
  d: path("M9 10a2.5 2.5 0 0 1 5 0c0 2 -2.5 2 -2.5 3.5");
}

.nj8530sxr {
  fill: currentColor;
  d: path("M10.5 15a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.okud9xj_d {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
