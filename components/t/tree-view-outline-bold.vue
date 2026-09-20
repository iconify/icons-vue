<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l8u0rbram"/><path class="q4yr01p9d"/><path class="i9dy6nm5t"/><path class="hfvs-qb2q"/><path class="p6_cldbhv"/><path class="z0r0_7bjh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tree-view-outline-bold" /></template>
<style>
.hfvs-qb2q {
  d: path("M11 11h10");
}

.i9dy6nm5t {
  d: path("M4 11h4");
}

.l8u0rbram {
  d: path("M4 4h17");
}

.p6_cldbhv {
  d: path("M4 18h4");
}

.q4yr01p9d {
  d: path("M4 4v14");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.z0r0_7bjh {
  d: path("M11 18h10");
}

</style>
