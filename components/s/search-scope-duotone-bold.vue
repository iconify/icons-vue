<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="txqgcyphc"/><path class="c1kziyotx"/><path class="hieqhxiaw"/><path class="uorymuo0h"/><path class="ldodvk1_f"/><path class="d6cu3qpew"/><path class="e5k2eotmk"/><path class="ei5j_bckv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:search-scope-duotone-bold" /></template>
<style>
.c1kziyotx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 3H3v18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.d6cu3qpew {
  d: path("M17 3h4v18h-4");
}

.e5k2eotmk {
  d: path("M9 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.ei5j_bckv {
  d: path("M11.5 11.5 15 15");
}

.hieqhxiaw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 3h4v18h-4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ldodvk1_f {
  d: path("M7 3H3v18h4");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.txqgcyphc {
  fill: currentColor;
  d: path("M9 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uorymuo0h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11.5 11.5 15 15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
