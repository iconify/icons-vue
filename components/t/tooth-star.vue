<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxn-5uu4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tooth-star" /></template>
<style>
.qxn-5uu4p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.695 12.598l.055-.348C16.25 10.5 17.5 9 17.5 6.5c0-2.25-.75-4-3-4c-1.75 0-2.75.75-4.5.75S7.25 2.5 5.5 2.5c-2.25 0-3 1.75-3 4c0 2.5 1.25 4 1.75 5.75L5 17c.25 1.5 2 1.5 2.5 0l1-3.25c.5-1.25 2.5-1.25 3 0l.83 2.697m5.934-1.405l.166.335a1.5 1.5 0 0 0 1.129.821l.37.053a.574.574 0 0 1 .318.979l-.268.26a1.5 1.5 0 0 0-.431 1.328l.063.368a.574.574 0 0 1-.832.605l-.331-.174a1.5 1.5 0 0 0-1.396 0l-.331.174a.574.574 0 0 1-.832-.605l.063-.368a1.5 1.5 0 0 0-.431-1.328l-.268-.26a.574.574 0 0 1 .318-.979l.37-.053a1.5 1.5 0 0 0 1.129-.821l.166-.335a.574.574 0 0 1 1.028 0");
}

</style>
