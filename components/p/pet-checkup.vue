<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ov4x7pmiv"/><path class="d_06rcwsq"/><path class="yn5i43bcr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pet-checkup" /></template>
<style>
.d_06rcwsq {
  d: path("M5.75 9.75v2.75q0 .104.005.209q.005.104.015.208q.011.103.026.207q.015.103.036.205t.045.204q.026.101.056.201t.065.198t.076.194q.039.097.084.191t.094.186t.103.182q.053.089.111.176t.12.171t.129.164t.136.158t.144.151t.151.144t.158.136q.08.066.164.129q.084.062.171.12t.176.111q.09.054.182.103t.186.094t.191.084t.194.076q.098.035.198.065t.201.056q.102.025.204.045q.102.021.205.036q.104.015.207.026q.104.01.208.015q.105.005.209.005q.222 0 .442-.023q.221-.023.438-.069t.428-.114t.414-.158t.395-.201q.192-.11.372-.24t.345-.278t.314-.312m.75-1.161q.352-.81.352-1.694V11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ov4x7pmiv {
  d: path("M3 2.75V7a2.75 2.75 0 0 0 5.5 0V2.75");
}

.yn5i43bcr {
  d: path("M11.25 8a3 3 0 1 0 6 0a3 3 0 1 0-6 0M16 20a2.5 1.75 0 1 0 5 0a2.5 1.75 0 1 0-5 0m-.25-3.75h.01m2.74-1.5h.01m2.74 1.5h.01");
}

</style>
