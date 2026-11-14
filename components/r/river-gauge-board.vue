<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yle0egb5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:river-gauge-board" /></template>
<style>
.yle0egb5v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 14.98V5.125q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T9.2 4.12q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087q.119.049.232.11t.221.132t.207.154t.191.173t.173.191t.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25t.037.255q.013.128.013.257v8.032m-.006 5.888q-.008.123-.027.245q-.02.123-.051.242q-.031.12-.073.236t-.095.228q-.052.112-.115.218q-.063.107-.136.207t-.155.192q-.082.093-.172.177q-.09.085-.188.161q-.098.075-.202.141q-.105.067-.215.123t-.225.101q-.115.046-.234.08q-.118.034-.24.058q-.121.023-.244.034t-.247.012h-.75q-.232 0-.46-.041q-.228-.04-.446-.12t-.418-.197t-.377-.268M9 5h3M9 9h3m-3 4h3M2 17q2.5-2 5 0t5 0t5 0t5 0");
}

</style>
