<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="f_v_dfbgn"/><circle class="bvk48sbfr"/><circle class="l0mg34bqc"/><path class="mdimy_3sv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mpv" /></template>
<style>
.bvk48sbfr {
  cx: 25.165px;
  cy: 22.721px;
  r: 16.612px;
}

.f_v_dfbgn {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
}

.l0mg34bqc {
  cx: 23.139px;
  cy: 24.408px;
  r: 10.762px;
}

.mdimy_3sv {
  d: path("m20.712 20.011l-.204 8.71l7.36-4.392z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
