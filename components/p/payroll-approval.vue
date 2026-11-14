<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m_zytub2l"/><path class="e9fltbcec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:payroll-approval" /></template>
<style>
.e9fltbcec {
  d: path("m14.75 18l2 2L21 15.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m_zytub2l {
  d: path("M6.125 3.5h9.75A2.625 2.625 0 0 1 18.5 6.125v.5a2.625 2.625 0 0 1-2.625 2.625h-9.75A2.625 2.625 0 0 1 3.5 6.625v-.5A2.625 2.625 0 0 1 6.125 3.5m.75 5.75h9.75a2.625 2.625 0 0 1 2.625 2.625v.5A2.625 2.625 0 0 1 16.625 15h-9.75a2.625 2.625 0 0 1-2.625-2.625v-.5A2.625 2.625 0 0 1 6.875 9.25m6.686 11.5H6.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063t-.243-.087q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257v-.5q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25t.087-.243t.11-.232q.061-.114.132-.221q.072-.108.154-.207q.082-.1.173-.191t.191-.173t.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q5.996 15 6.125 15h9.75q.394 0 .772.116q.377.116.703.338M7 5.5v1.75m4-1.75v1.75m4-1.75v1.75m-7.25 4V13m4-1.75V13m4-1.75V13M7 17v1.75M11 17v1.75");
}

</style>
