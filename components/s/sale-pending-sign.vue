<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g4j471bsw"/><path class="rjb84ybnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sale-pending-sign" /></template>
<style>
.g4j471bsw {
  d: path("M3.5 21.5v-19m0 2.5h17m-8.989 13.5H9.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T8.12 18.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173t-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257v-5.75q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T6.7 9.12q.049-.119.11-.232t.132-.221t.154-.207q.082-.1.173-.191t.191-.173t.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h8.25q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11q.114.061.221.132q.108.072.207.154q.1.082.191.173t.173.191q.082.099.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v1.632M9 5v2.5M17.5 5v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rjb84ybnu {
  d: path("M14.25 18a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m2.5-1.5v3m2.5-3v3");
}

</style>
