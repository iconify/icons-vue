<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ocyf5ip6z"/><path class="beyv8obcn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:prescription-mental" /></template>
<style>
.beyv8obcn {
  d: path("m8.672 10.354l3.182-3.182a1.75 1.75 0 0 1 2.474 0a1.75 1.75 0 0 1 0 2.474l-3.182 3.182a1.75 1.75 0 0 1-2.474 0a1.75 1.75 0 0 1 0-2.474m1.591-1.591l2.474 2.474");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ocyf5ip6z {
  d: path("M8 21.5v-4c-2.5-1.75-3.5-4.25-3.5-7C4.5 6.25 7.75 3 12 3c4 0 7 2.75 7 6.75l1.5 3.5c.25.5-.1 1-.75 1H19v2.25c0 1.1-.9 2-2 2h-2v3");
}

</style>
