<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s1aem-olr"/><ellipse class="e5kpvpb1p"/><path class="h6b224b6c"/><path class="y0ui4kbla"/><ellipse class="vicsqablu"/><path class="ve_xmcx7a"/><ellipse class="ismzzbctk"/><path class="z_i8820zz"/><circle class="cpk0fnbgt"/><path class="ww6z_4c0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sbb-inclusive" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.e5kpvpb1p {
  cx: 24px;
  cy: 25.666px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.273px;
  ry: 3.21px;
}

.h6b224b6c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.333 30.624C9.856 31.38 9 32.277 9 33.24c0 2.697 6.716 4.883 15 4.883s15-2.186 15-4.883c0-.962-.856-1.86-2.333-2.616m-14.922-5.356a5 5 0 0 0-.75-.47");
}

.ismzzbctk {
  cx: 28.837px;
  cy: 22.901px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.273px;
  ry: 3.21px;
}

.s1aem-olr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.17 27.561c-2.116 1.063-3.63 3.916-3.63 7.268h10.92c0-3.352-1.513-6.204-3.628-7.267");
}

.ve_xmcx7a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.099 32.064h5.199c0-3.351-1.514-6.203-3.629-7.267m-3.662 0a5 5 0 0 0-.752.471");
}

.vicsqablu {
  cx: 19.163px;
  cy: 22.901px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.273px;
  ry: 3.21px;
}

.ww6z_4c0i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.421 15.318h39.158");
}

.y0ui4kbla {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.332 24.797c-2.116 1.063-3.63 3.915-3.63 7.267H18.9");
}

.z_i8820zz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.87 6.041l2.865 2.868l-2.867 2.867m-5.739 0L18.265 8.91l2.867-2.868m-2.867 2.867h11.47M24 6.041v5.736");
}

</style>
