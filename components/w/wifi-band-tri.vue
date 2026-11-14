<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qtvpbdc_q"/><path class="i_arevbjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wifi-band-tri" /></template>
<style>
.i_arevbjp {
  d: path("M5 11.5a7.5 7.5 0 0 1 12 0m-9 2.25q.061-.081.126-.159q.065-.077.134-.152q.07-.074.143-.144t.15-.136t.157-.128t.163-.12t.17-.11t.176-.101t.181-.092t.186-.081q.093-.038.189-.071t.194-.061t.196-.051t.199-.04q.1-.017.2-.029q.101-.011.202-.018t.203-.007q.101-.001.202.004t.202.015t.201.025q.101.016.2.037t.197.047t.194.058t.191.068t.187.078t.182.089t.178.098t.172.107t.165.117q.082.06.16.125q.077.065.152.134q.074.069.144.142M11 16h.01m5.49-.5H21l-2 2a2 2 0 1 1-1.5 3.5");
}

.qtvpbdc_q {
  d: path("M2 9.25a11.25 11.25 0 0 1 18 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
