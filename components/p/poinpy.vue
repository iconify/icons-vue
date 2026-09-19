<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yyjt_kanz"/><path class="ndxp_sb0k"/><circle class="mxl-hqbdo"/><circle class="evsh46l5b"/><path class="g4m69iroj"/><path class="zkdb1-rhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:poinpy" /></template>
<style>
.evsh46l5b {
  cx: 33.571px;
  cy: 24.782px;
  r: 1.987px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.g4m69iroj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.612 35.742c-1.458 2.34-1.779 5.788 1.587 7.43s7.05-3.295 7.595-5.378m.354-25.73c0 1.6 2.691 2.333 4.582 2.333s3.363-.498 4.117-2.028c0-1.562-.88-3.709-4.213-3.709s-4.486 1.904-4.486 3.404");
}

.mxl-hqbdo {
  cx: 22.506px;
  cy: 23.5px;
  r: 1.987px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ndxp_sb0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.609 15.359C20.262 9.846 15.84 1.962 10.327 5.295s-.82 16.638-.82 16.638a14.26 14.26 0 0 1-4.436 5.348c3.653 5.705 7.82 10.513 18.973 10.513a32 32 0 0 0 7.67-.815");
}

.yyjt_kanz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.722 12.554a21 21 0 0 1 2.426-.49M40.42 28.431a13 13 0 0 0 .098-1.598c0-7.105-2.972-12.684-8.67-14.464");
}

.zkdb1-rhb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.634 8.66c-3.333 0-4.486 1.904-4.486 3.404a4.81 4.81 0 0 0 4.582 2.333m8.39.431c1.77-3.251 1.77-9.597-1.595-10.046s-5.32 3.878-5.32 3.878m2.379 27.916c.73 2.704 3.358 3.397 6.755 1.474s5.77-5.127 3.974-8.237s-6.73-.256-8.59 1.57s-2.73 3-2.139 5.193");
}

</style>
