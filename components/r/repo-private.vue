<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lx6owjb_r"/><path class="i2_9pcbfw"/><path class="sye78vbzq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:repo-private" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i2_9pcbfw {
  d: path("M12.211 19H5.625q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.62 18.8q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255Q3 16.504 3 16.375v-5.25q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25t.087-.243q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173t.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h10.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11t.221.132t.207.154q.1.082.191.173t.173.191q.082.099.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v.432M11 3.5v5m5.75 8.5h2.5A1.75 1.75 0 0 1 21 18.75v1a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.75v-1A1.75 1.75 0 0 1 16.75 17");
}

.lx6owjb_r {
  d: path("m3 8.5l2.5-5h11l2.5 5");
}

.sye78vbzq {
  d: path("M16.25 17v-1a1.75 1.75 0 0 1 3.5 0v1");
}

</style>
