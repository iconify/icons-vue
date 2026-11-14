<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x8fptkbol"/><path class="lgmb0bmvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:map-search-area" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lgmb0bmvo {
  d: path("M8.233 14.971q-.115-.018-.229-.045q-.113-.028-.223-.065q-.111-.038-.217-.085q-.107-.047-.209-.104t-.199-.121q-.097-.066-.187-.139q-.091-.074-.174-.155q-.084-.082-.16-.17t-.144-.183t-.127-.195q-.059-.101-.109-.206q-.051-.106-.091-.215q-.041-.109-.071-.222q-.031-.112-.052-.227t-.031-.231t-.01-.233v-1.25q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25t.087-.243q.049-.119.11-.232t.132-.221t.154-.207q.082-.1.173-.191t.191-.173t.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h1.75q.58 0 1.106.244M11 14a3 3 0 1 0 6 0a3 3 0 1 0-6 0m5.25 2.25L20 20");
}

.x8fptkbol {
  d: path("m16.31 20.23l-.81.27l-7-2l-6 2v-15l6-2l7 2l6-2v14.071");
}

</style>
