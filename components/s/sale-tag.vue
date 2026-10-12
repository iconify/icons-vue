<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qnq0mhbyd"/><circle class="bfo0bhbkc"/><path class="mk3bucb2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sale-tag" /></template>
<style>
.bfo0bhbkc {
  cx: 7px;
  cy: 12px;
  r: 1.1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mk3bucb2v {
  d: path("m15.28 7.79l.74.78q.28.29.68.28l1.08-.02q.4-.01.39.39l-.02 1.08q-.01.4.28.68l.78.74q.29.28 0 .56l-.78.74q-.29.28-.28.68l.02 1.08q.01.4-.39.39l-1.08-.02q-.4-.01-.68.28l-.74.78q-.28.29-.56 0l-.74-.78q-.28-.29-.68-.28l-1.08.02q-.4.01-.39-.39l.02-1.08q.01-.4-.28-.68l-.78-.74q-.29-.28 0-.56l.78-.74q.29-.28.28-.68l-.02-1.08q-.01-.4.39-.39l1.08.02q.4.01.68-.28l.74-.78q.28-.29.56 0m-1.53 5.71l2.5-3");
}

.qnq0mhbyd {
  d: path("M8.66 5.75h10.59a2 2 0 0 1 2 2v8.5a2 2 0 0 1-2 2H8.66a2 2 0 0 1-1.48-.66l-3.86-4.25a2 2 0 0 1 0-2.68l3.86-4.25a2 2 0 0 1 1.48-.66");
}

</style>
