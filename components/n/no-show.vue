<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u20_8bb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:no-show" /></template>
<style>
.u20_8bb_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.125 2.5h3.75A2.625 2.625 0 0 1 13.5 5.125v1.75A2.625 2.625 0 0 1 10.875 9.5h-3.75A2.625 2.625 0 0 1 4.5 6.875v-1.75A2.625 2.625 0 0 1 7.125 2.5M13.086 13H4.25q-.061 0-.123-.006q-.061-.006-.121-.018t-.119-.03t-.115-.041t-.111-.053t-.105-.063t-.099-.073t-.091-.082q-.043-.044-.082-.091t-.073-.099t-.063-.105t-.053-.111q-.023-.056-.041-.115t-.03-.119t-.018-.121T3 11.75t.006-.123t.018-.121t.03-.119t.041-.115q.024-.057.053-.111t.063-.105t.073-.099t.082-.091t.091-.082t.099-.073t.105-.063t.111-.053q.056-.023.115-.041t.119-.03t.121-.018q.062-.006.123-.006h9.5q.061 0 .123.006q.061.006.121.018t.119.03t.115.041t.111.053t.105.063t.099.073t.091.082q.043.044.082.091t.073.099t.063.105t.053.111q.023.056.041.115t.03.119t.018.121t.006.123q0 .233-.084.45M4.5 13L4 20m2.5-7v4.5m5-4.5v4.5M15 15l6 6m0-6l-6 6");
}

</style>
