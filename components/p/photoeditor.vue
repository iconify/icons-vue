<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="jrq72-2nz"/><path class="k81tqll1v"/><circle class="qsbqk946e"/><circle class="u67vhsf4c"/><path class="mrfx83yba"/><circle class="c4s8jvbhj"/><path class="z_vkg1klp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:photoeditor" /></template>
<style>
.c4s8jvbhj {
  cx: 35.143px;
  cy: 32.747px;
  r: 1.672px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jrq72-2nz {
  cx: 41.828px;
  cy: 32.747px;
  r: 1.672px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k81tqll1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m37.938 36.647l-31.691-.031a1.636 1.636 0 0 1-1.747-1.41l.008-19.404a1.62 1.62 0 0 1 1.77-1.435l30.38-.005c.963.02 1.817.59 1.77 1.54l.057 9.667");
}

.mrfx83yba {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.014 17.147H35.7v2.229h-6.686zm-21.74-5.794h5.595v3.021H7.274z");
}

.qsbqk946e {
  cx: 21.771px;
  cy: 26.619px;
  r: 7.416px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.u67vhsf4c {
  cx: 14.528px;
  cy: 18.262px;
  r: 1.114px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z_vkg1klp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.27 31.515l6.672-7.125m-2.294 7.177l-6.62-7.177");
}

</style>
