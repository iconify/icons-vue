<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ru9t36b4k"/><path class="w77507--d"/><path class="qux3mqb3d"/><path class="fht3habxh"/><path class="wr_ld5s1h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pipeline-ci-outline-regular" /></template>
<style>
.fht3habxh {
  d: path("M19.5 10v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qux3mqb3d {
  d: path("M17 4.5A2.5 2.5 0 0 1 19.5 2 2.5 2.5 0 0 1 22 4.5 2.5 2.5 0 0 1 19.5 7 2.5 2.5 0 0 1 17 4.5");
}

.ru9t36b4k {
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2 2.5 2.5 0 0 1 7 4.5 2.5 2.5 0 0 1 4.5 7 2.5 2.5 0 0 1 2 4.5");
}

.w77507--d {
  d: path("M9.5 4.5A2.5 2.5 0 0 1 12 2a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 12 7a2.5 2.5 0 0 1 -2.5 -2.5");
}

.wr_ld5s1h {
  d: path("M17 19.5a2.5 2.5 0 0 1 2.5 -2.5 2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5 2.5 2.5 0 0 1 -2.5 -2.5");
}

</style>
