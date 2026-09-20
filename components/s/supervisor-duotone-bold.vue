<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q4syl0bov"/><path class="hjp8h-x2r"/><path class="kh6d2du6i"/><path class="d-ear9ieq"/><path class="co1wtzbml"/><path class="d-tnphbnb"/><path class="mq1k2k45m"/><path class="i8t3_pbsa"/><path class="cuxt49b2j"/><path class="vs9lv0b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:supervisor-duotone-bold" /></template>
<style>
.co1wtzbml {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14.5 10.5 2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cuxt49b2j {
  d: path("m9.5 10.5 -2 2");
}

.d-ear9ieq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9.5 10.5 -2 2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d-tnphbnb {
  d: path("M13.27 5.28a3 3 0 1 1 -2.54 0");
}

.hjp8h-x2r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6.27 12.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.i8t3_pbsa {
  d: path("M20.27 12.28a3 3 0 1 1 -2.54 0");
}

.kh6d2du6i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20.27 12.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mq1k2k45m {
  d: path("M6.27 12.28a3 3 0 1 1 -2.54 0");
}

.q4syl0bov {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13.27 5.28a3 3 0 1 1 -2.54 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vs9lv0b4s {
  d: path("m14.5 10.5 2 2");
}

</style>
