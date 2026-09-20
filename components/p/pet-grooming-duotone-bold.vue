<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="wwbr61vxt"/><path class="i3cv35p_l"/><path class="ktxjg3b2q"/><path class="evsu0jbbm"/><path class="drjad9bfe"/><path class="rgnpgnbjr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pet-grooming-duotone-bold" /></template>
<style>
.drjad9bfe {
  d: path("M14 14v4");
}

.evsu0jbbm {
  d: path("M10 14v4");
}

.i3cv35p_l {
  d: path("M4 8a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.ktxjg3b2q {
  d: path("M6 14v4");
}

.rgnpgnbjr {
  d: path("M16 10h5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wwbr61vxt {
  fill: currentColor;
  d: path("M4 8a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
