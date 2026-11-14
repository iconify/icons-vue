<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gjgu8ij5s"/><path class="qfmj_zjmc"/><path class="nr2kwkbiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:premium-amount" /></template>
<style>
.gjgu8ij5s {
  d: path("M11.254 18.304q-.314-.093-.596-.26q-.282-.168-.514-.4l-6.375-6.375q-.183-.183-.326-.398t-.243-.454q-.099-.238-.15-.492Q3 9.672 3 9.413V5.625q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T3.2 4.62q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q5.496 3 5.625 3h3.788q.259 0 .512.05q.254.051.492.15q.239.099.454.243q.215.143.398.326l6.375 6.375q.2.2.353.438t.251.503q.099.266.139.546q.039.28.019.562");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nr2kwkbiv {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

.qfmj_zjmc {
  d: path("M6 7.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

</style>
