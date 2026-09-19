<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse transform="rotate(-13.798 37.914 17.07)" class="w7-hlub6g"/><ellipse transform="rotate(-13.798 10.086 22.52)" class="r-t8tp6qs"/><path class="hge7n4fmm"/><circle class="z4pzyh_uc"/><path class="ne_mskbnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tune-it" /></template>
<style>
.hge7n4fmm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.329 17.784v18.694L5.5 42.44V23.255");
}

.ne_mskbnb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.844 36.01l.012-9.281m-2.321-21.17v18.784c0 3.198 4.482 3.209 4.482-.113V5.559");
}

.r-t8tp6qs {
  cx: 10.086px;
  cy: 22.519px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.655px;
  ry: 3.201px;
}

.w7-hlub6g {
  cx: 37.914px;
  cy: 17.071px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.655px;
  ry: 3.201px;
}

.z4pzyh_uc {
  cx: 21.844px;
  cy: 37.458px;
  r: 1.448px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
