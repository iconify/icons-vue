<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kxq8g7bho"/><path class="t3qn5ubhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:paper-stack-plus" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kxq8g7bho {
  d: path("M15.248 21.112q-.31.19-.66.289t-.713.099h-7.75q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T5.12 21.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257V8.625q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T3.7 7.62t.11-.232t.132-.221t.154-.207q.082-.1.173-.191t.191-.173t.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q5.996 6 6.125 6h7.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087q.119.049.232.11t.221.132t.207.154q.1.082.191.173t.173.191t.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v4.032");
}

.t3qn5ubhe {
  d: path("M7 2.5h11.5a2 2 0 0 1 2 2v8M18 15v6m-3-3h6");
}

</style>
