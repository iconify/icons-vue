<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rm4ndpb9g"/><path class="homo6573s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:repo-security" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.homo6573s {
  d: path("m18 13l4 1.5v3c0 2.25-1.75 3.75-4 4.5c-2.25-.75-4-2.25-4-4.5v-3Z");
}

.rm4ndpb9g {
  d: path("M2.5 8L5 3h10.5L18 8m-6.789 10.5H5.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.12 18.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257v-5.25q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T2.7 9.62q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173t.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q4.996 8 5.125 8h10.25q.115 0 .229.01q.115.01.228.03t.224.05t.219.069t.213.088t.203.107t.194.124q.094.066.182.14t.169.155q.081.082.154.17q.074.088.14.183q.065.094.123.194t.105.204t.087.213t.068.219t.049.224M10.25 3v5");
}

</style>
