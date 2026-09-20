<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="nwys7tb-b"/><path class="y8h-esezl"/><path class="c5icmybsm"/><path class="naf5gjb6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:release-duotone-bold" /></template>
<style>
.c5icmybsm {
  d: path("m4 12 6 -6h10v12H10Z");
}

.naf5gjb6k {
  d: path("M12 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.nwys7tb-b {
  fill: currentColor;
  d: path("m4 12 6 -6h10v12H10Z");
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

.y8h-esezl {
  fill: currentColor;
  d: path("M12 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
