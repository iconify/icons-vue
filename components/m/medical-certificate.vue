<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s-mu_fbjv"/><path class="com3gja5u"/><path class="se7ojnbth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:medical-certificate" /></template>
<style>
.com3gja5u {
  fill: currentColor;
  d: path("M5.75 6.75h2.5v2h2v2.5h-2v2h-2.5v-2h-2v-2.5h2Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s-mu_fbjv {
  d: path("M12.011 17H5.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.12 16.8q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25t-.037-.255q-.013-.128-.013-.257v-8.25q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T2.7 5.12q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h13.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11q.114.061.221.132q.108.072.207.154q.1.082.191.173t.173.191t.154.207t.132.221t.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v6.532");
}

.se7ojnbth {
  d: path("M12.5 8H17m-4.5 3H15m-.25 5.5a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m1.5 2.5l-.75 2.75M18.75 19l.75 2.75");
}

</style>
