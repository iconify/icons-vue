<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc4h4kbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:navigation-off" /></template>
<style>
.qc4h4kbxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.561 6.601q.121-.174.28-.315t.347-.239q.188-.099.394-.149q.206-.051.418-.051q.129 0 .257.019t.252.056q.123.038.24.093q.117.056.225.128q.107.072.203.158q.095.087.177.187t.148.211t.116.231l1.942 4.716m-3.223 4.652q-.309-.06-.62-.009t-.585.207L8.5 18q-.093.053-.194.092q-.1.038-.205.06t-.212.028t-.214-.005t-.211-.038t-.203-.07t-.189-.101q-.09-.057-.171-.128t-.149-.153q-.069-.083-.124-.175q-.056-.092-.096-.192q-.04-.099-.065-.204q-.024-.104-.032-.212q-.008-.107 0-.214t.034-.211q.025-.105.066-.204l1.701-4.132M3.5 3.5l17 17");
}

</style>
