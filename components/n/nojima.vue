<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mrwdwlwsz"/><path class="ixau__bmv"/><circle class="klhpp1jbp"/><path class="wxeteq89s"/><circle class="l--3muzsw"/><path class="xma40h-gi"/><path class="m0jcw_ecq"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nojima" /></template>
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

.ixau__bmv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.719 24.12a2.252 2.252 0 1 1 4.504 0v3.716");
}

.klhpp1jbp {
  cx: 24.084px;
  cy: 19.107px;
  r: 0.75px;
  fill: currentColor;
}

.l--3muzsw {
  cx: 21.954px;
  cy: 19.164px;
  r: 0.75px;
  fill: currentColor;
}

.m0jcw_ecq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.472 22.458c.542-.544.923-.591 1.97-.591c1.19 0 1.971.523 1.971 1.937v4.031M15.546 24.12a2.252 2.252 0 1 1 4.504 0v1.463a2.252 2.252 0 1 1-4.504 0zm-6.519-6.128a3.22 3.22 0 0 1 4.72 1.954");
}

.mrwdwlwsz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.214 24.12a2.252 2.252 0 1 1 4.505 0v3.716m-4.505-5.969v5.968");
}

.wxeteq89s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.084 21.867v5.968m-2.13-5.968v6.757a2.24 2.24 0 0 1-2.23 2.252a2.2 2.2 0 0 1-1.579-.66");
}

.xma40h-gi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.856 27.835v-6.184m-6.439 6.184V17.124m33.996 8.459c0 1.244-1 2.252-2.235 2.252h-.785c-.818 0-1.48-.668-1.48-1.492s.662-1.492 1.48-1.492h3.024");
}

</style>
