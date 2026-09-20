<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="llg_lb3ns"/><path class="qt24fkw_c"/><path class="c3rn_7bqc"/><path class="v6j2lm37i"/><path class="hijsj72qe"/><path class="khg27_bvg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tuition-duotone-bold" /></template>
<style>
.c3rn_7bqc {
  d: path("M2 9a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.hijsj72qe {
  d: path("M6 10v5");
}

.khg27_bvg {
  d: path("M18 10v5");
}

.llg_lb3ns {
  fill: currentColor;
  d: path("M2 9a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v7a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qt24fkw_c {
  fill: currentColor;
  d: path("M9 12.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.v6j2lm37i {
  d: path("M9 12.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
