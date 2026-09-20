<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pm30vmtce"/><path class="xr2rcq_ip"/><path class="qtxvlht3c"/><path class="vc2-n5bxy"/><path class="w_nev909g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:matchmaking-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pm30vmtce {
  d: path("M2 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.qtxvlht3c {
  d: path("M8 17h8");
}

.vc2-n5bxy {
  d: path("m11 14 -3 3 3 3");
}

.w_nev909g {
  d: path("m13 14 3 3 -3 3");
}

.xr2rcq_ip {
  d: path("M14 9a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
