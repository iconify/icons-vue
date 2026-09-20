<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y4_6s7b5v"/><path class="dg_gji4cg"/><path class="j9sqoabvp"/><path class="b-csqm2-o"/><path class="x0t1t4bmb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mark-scheme-outline-bold" /></template>
<style>
.b-csqm2-o {
  d: path("m7 15 2 2 3 -3");
}

.dg_gji4cg {
  d: path("m7 8 2 2 3 -3");
}

.j9sqoabvp {
  d: path("M15 9h3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x0t1t4bmb {
  d: path("M15 16h3");
}

.y4_6s7b5v {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
