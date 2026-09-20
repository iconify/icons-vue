<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="yxjvqtiry"/><path class="nyh3160vb"/><path class="leql65bnu"/><path class="qe97cg-lx"/><path class="hj1fiqb-o"/><path class="bd3-a5q0s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:roc-curve-duotone-bold" /></template>
<style>
.bd3-a5q0s {
  d: path("M6 18 18 6");
}

.hj1fiqb-o {
  d: path("M6 18v-6l6 -6h6");
}

.leql65bnu {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 18 18 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nyh3160vb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 18v-6l6 -6h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qe97cg-lx {
  d: path("M3 3v18h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yxjvqtiry {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 3v18h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
