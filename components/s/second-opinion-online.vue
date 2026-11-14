<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wwjmdpb2j"/><path class="o8g7g5u1j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:second-opinion-online" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o8g7g5u1j {
  d: path("M7.5 7.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-1.25 4c0-1.25 1.25-2 2.75-2s2.75.75 2.75 2M15.5 16c0-1.25 1-1.75 2.25-1.75s2.25.75 2.25 2c0 1.5-2 2.5-4.5 5.25h5");
}

.wwjmdpb2j {
  d: path("M13.011 14H6.625q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T5.62 13.8q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173t-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25t-.037-.255Q4 11.504 4 11.375v-5.25q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T4.2 5.12q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h9.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11q.114.061.221.132q.108.072.207.154q.1.082.191.173t.173.191t.154.207t.132.221t.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v5.25q0 .085-.006.17M2.5 17h10.4");
}

</style>
