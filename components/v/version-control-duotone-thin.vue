<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vxdgzqbaj"/><path class="ld7zhcybq"/><path class="gob4qybps"/><path class="qcol0s9_v"/><path class="r0e633-if"/><path class="t1sjjacis"/><path class="u_41jqbcx"/><path class="h36909btm"/><path class="o759xmblc"/><path class="nvdm6duxk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:version-control-duotone-thin" /></template>
<style>
.gob4qybps {
  fill: currentColor;
  d: path("M16 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.h36909btm {
  d: path("M16 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ld7zhcybq {
  fill: currentColor;
  d: path("M4 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nvdm6duxk {
  d: path("M8 6h4l4 4");
}

.o759xmblc {
  d: path("M6 8v8");
}

.qcol0s9_v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 8v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r0e633-if {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 6h4l4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t1sjjacis {
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.u_41jqbcx {
  d: path("M4 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.vxdgzqbaj {
  fill: currentColor;
  d: path("M4 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
