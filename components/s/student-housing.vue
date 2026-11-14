<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kqfja3chw"/><path class="qzmk_wbta"/><path class="oonqshkqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:student-housing" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kqfja3chw {
  d: path("M13.311 21.5H7.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T6.12 21.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257V5.125q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T4.7 4.12q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h9.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11q.114.061.221.132q.108.072.207.154q.1.082.191.173t.173.191t.154.207t.132.221t.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v7.732M8 6.5h1.5m5 0H16m-8 4h1.5m5 0H16m-8 4h1.5");
}

.oonqshkqs {
  d: path("M15.75 17.75v2c0 .75 1 1.25 2.25 1.25s2.25-.5 2.25-1.25v-2");
}

.qzmk_wbta {
  d: path("M10.5 21.5v-3.25h2.45M16.375 16l.996-.46a1.5 1.5 0 0 1 1.258 0l.996.46a.826.826 0 0 1 0 1.5l-.996.46a1.5 1.5 0 0 1-1.258 0l-.996-.46a.826.826 0 0 1 0-1.5");
}

</style>
