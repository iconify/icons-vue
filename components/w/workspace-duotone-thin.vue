<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g7d56fjnv"/><path class="vfnv_-9js"/><path class="zw76b7msm"/><path class="vyks9vbfn"/><path class="t87ohzbeq"/><path class="mnt4e8bcf"/><path class="tkgsjrp5m"/><path class="okg0-qwlz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:workspace-duotone-thin" /></template>
<style>
.g7d56fjnv {
  fill: currentColor;
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mnt4e8bcf {
  d: path("M9 11h13");
}

.okg0-qwlz {
  d: path("M4.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.t87ohzbeq {
  d: path("M9 4v16");
}

.tkgsjrp5m {
  d: path("M4.5 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.vfnv_-9js {
  fill: currentColor;
  d: path("M4.5 8a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.vyks9vbfn {
  d: path("M2 6a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.zw76b7msm {
  fill: currentColor;
  d: path("M4.5 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
