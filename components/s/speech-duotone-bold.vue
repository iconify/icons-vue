<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="j4z1smu9o"/><path class="oec57-4mx"/><path class="cs9f_sbcc"/><path class="c664ux15j"/><path class="yjzas4brk"/><path class="lbz2yq5no"/><path class="el0n_ccnv"/><path class="h7bcztycq"/><path class="cg-q-7bgo"/><path class="om2raabrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:speech-duotone-bold" /></template>
<style>
.c664ux15j {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cg-q-7bgo {
  d: path("M16 3v18");
}

.cs9f_sbcc {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.el0n_ccnv {
  d: path("M8 5v14");
}

.h7bcztycq {
  d: path("M12 8v8");
}

.j4z1smu9o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 9v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lbz2yq5no {
  d: path("M4 9v6");
}

.oec57-4mx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.om2raabrv {
  d: path("M20 10v4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.yjzas4brk {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 10v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
