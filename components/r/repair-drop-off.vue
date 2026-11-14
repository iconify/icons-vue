<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gomeag1co"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:repair-drop-off" /></template>
<style>
.gomeag1co {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.011 21.5H5.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.12 21.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257v-4.25q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25t.087-.243q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173t.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q4.996 12 5.125 12h11.7m2.381.021q.117.015.233.04t.229.062q.113.035.222.081q.11.046.214.102q.105.055.204.12q.1.065.193.138t.179.155t.165.171q.078.089.148.184q.07.096.131.198q.061.101.113.208t.094.217t.073.226q.032.114.053.231q.022.116.032.234t.011.237v1.132M2.5 15h12.7m5.6 0h.7m-14-3l1.25-4.75m2.224-3.696a2.25 2.25 0 1 1-3.448 0M15.5 2.5za2 2 0 0 1 2 2V7a2 2 0 0 1-2 2a2 2 0 0 1-2-2V4.5a2 2 0 0 1 2-2m0 6.5v3m2.5 2.5v7m-3-3l3 3l3-3");
}

</style>
