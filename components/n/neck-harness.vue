<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tpb5mcclc"/><path class="xhi2skb9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:neck-harness" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tpb5mcclc {
  d: path("M8.75 21.5V14C6.75 12.75 6 10.75 6 8.5c0-3.5 2.5-6 6-6c3.25 0 5.5 2.25 5.5 5.5l1.25 2.75c.25.5 0 .75-.5.75h-.75v1.75c0 .75-.75 1.5-1.5 1.5h-1.5v6.75");
}

.xhi2skb9d {
  d: path("M6.75 18.5a5 1.75 0 1 0 10 0a5 1.75 0 1 0-10 0m10 0c3 0 3.75 1 3.75 3");
}

</style>
