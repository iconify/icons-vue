<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p2v4iydux"/><path class="ho0333w0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-chocolate" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ho0333w0b {
  d: path("m3 8l2 1.5L7 8l2 1.5L11 8l2 1.5L15 8M9 9.5v12m-6-8h12m-12 4h10.2M19 22l-2.25-2.75a2.75 2.75 0 1 1 4.5 0Z");
}

.p2v4iydux {
  d: path("M14.326 20.631q-.185.205-.408.368q-.223.162-.475.274t-.522.17q-.27.057-.546.057h-6.75q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.62 21.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255Q3 19.004 3 18.875V5.125q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T3.2 4.12q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h6.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087q.119.049.232.11t.221.132t.207.154t.191.173t.173.191t.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25t.037.255q.013.128.013.257v8.732");
}

</style>
