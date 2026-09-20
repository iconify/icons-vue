<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hr6yi9b8a"/><path class="wy_1lddne"/><path class="xkimj5b-x"/><path class="wko3ej0az"/><path class="viv5gg8xx"/><path class="rw6ho_bav"/><path class="ils7yp4cg"/><path class="pa38cub_q"/><path class="a3hpkcc6o"/><path class="ls7ugdcwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rack-duotone-thin" /></template>
<style>
.a3hpkcc6o {
  d: path("M6 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hr6yi9b8a {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ils7yp4cg {
  d: path("M2 16h20");
}

.ls7ugdcwr {
  d: path("M6 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.pa38cub_q {
  d: path("M6 5.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.rw6ho_bav {
  d: path("M2 9h20");
}

.viv5gg8xx {
  d: path("M2 4a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.wko3ej0az {
  fill: currentColor;
  d: path("M6 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wy_1lddne {
  fill: currentColor;
  d: path("M6 5.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xkimj5b-x {
  fill: currentColor;
  d: path("M6 12.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
