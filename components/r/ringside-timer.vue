<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ib6om8bke"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ringside-timer" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ib6om8bke {
  d: path("M13.949 13.5H2.5q0-.172.008-.343t.026-.343q.017-.171.042-.341t.059-.339q.033-.168.075-.335t.091-.331t.108-.326t.124-.321t.139-.314t.155-.307t.169-.299t.184-.29t.198-.281t.211-.271t.224-.26t.237-.249t.249-.237t.26-.224t.271-.211t.281-.198t.29-.184t.299-.169t.307-.155q.155-.073.314-.139t.321-.124t.326-.108t.331-.091t.335-.075q.169-.034.339-.059t.341-.042t.343-.026Q9.328 6.5 9.5 6.5q.303 0 .604.026t.6.078q.298.052.59.13q.293.077.577.18q.285.102.56.229t.537.277t.512.322t.482.365t.449.405q.215.212.412.442t.372.476q.176.247.33.507t.285.533t.238.556t.189.574t.139.589M2.5 16.5h9.6m-2.6-14v4M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

</style>
