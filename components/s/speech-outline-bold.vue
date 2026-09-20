<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="lbz2yq5no"/><path class="el0n_ccnv"/><path class="h7bcztycq"/><path class="cg-q-7bgo"/><path class="om2raabrv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:speech-outline-bold" /></template>
<style>
.cg-q-7bgo {
  d: path("M16 3v18");
}

.el0n_ccnv {
  d: path("M8 5v14");
}

.h7bcztycq {
  d: path("M12 8v8");
}

.lbz2yq5no {
  d: path("M4 9v6");
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

</style>
