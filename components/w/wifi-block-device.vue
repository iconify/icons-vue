<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwcr-eb-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:wifi-block-device" /></template>
<style>
.cwcr-eb-u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.411 15.75H6.625q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063t-.243-.087q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173t-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25t-.037-.255Q4 13.254 4 13.125v-3.25q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T4.2 8.87q.049-.119.11-.232t.132-.221t.154-.207q.082-.1.173-.191t.191-.173t.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h8.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11q.114.061.221.132q.108.072.207.154q.1.082.191.173t.173.191t.154.207t.132.221t.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v2.032M2.5 18.75H12M8 4.25a4.5 4.5 0 0 1 6 0M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m1-2.25l4.5 4.5");
}

</style>
