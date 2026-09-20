<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="w1wi7obvc"/><path class="vyrk3096t"/><path class="pm30vmtce"/><path class="xr2rcq_ip"/><path class="qtxvlht3c"/><path class="vc2-n5bxy"/><path class="w_nev909g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:matchmaking-duotone-bold" /></template>
<style>
.pm30vmtce {
  d: path("M2 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.qtxvlht3c {
  d: path("M8 17h8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vc2-n5bxy {
  d: path("m11 14 -3 3 3 3");
}

.vyrk3096t {
  fill: currentColor;
  d: path("M14 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.w_nev909g {
  d: path("m13 14 3 3 -3 3");
}

.w1wi7obvc {
  fill: currentColor;
  d: path("M2 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xr2rcq_ip {
  d: path("M14 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
