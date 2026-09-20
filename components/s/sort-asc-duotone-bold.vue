<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="e63e9dbag"/><path class="kaukupb-u"/><path class="km2_vvbqp"/><path class="mt0duqbnk"/><path class="xlekzhbnl"/><path class="o8od38cnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sort-asc-duotone-bold" /></template>
<style>
.e63e9dbag {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kaukupb-u {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.km2_vvbqp {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mt0duqbnk {
  d: path("M4 6h6");
}

.o8od38cnm {
  d: path("M4 18h16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xlekzhbnl {
  d: path("M4 12h11");
}

</style>
