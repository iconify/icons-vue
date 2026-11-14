<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="szwsbdyep"/><path class="hbv8nob4p"/><path class="trn1rwa5g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:remote-patient-monitoring" /></template>
<style>
.hbv8nob4p {
  d: path("M6.5 9h2l1.25-2.5l1.5 5L12.5 9h4m-2.25 9L18 14.5l3.75 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.szwsbdyep {
  d: path("M14.411 14H6.625q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T5.62 13.8q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173t-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25t-.037-.255Q4 11.504 4 11.375v-5.25q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T4.2 5.12q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h9.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11q.114.061.221.132q.108.072.207.154q.1.082.191.173t.173.191t.154.207t.132.221t.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v5.25q0 .231-.04.458M2.5 17h9.1");
}

.trn1rwa5g {
  d: path("M15.5 17v4.5h5V17");
}

</style>
