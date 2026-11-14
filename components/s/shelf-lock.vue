<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pc8f15m6q"/><path class="h9k05gb-h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shelf-lock" /></template>
<style>
.h9k05gb-h {
  d: path("M6.5 10.5V6l1-1V3H9v2l1 1v4.5m4-6h3A1.5 1.5 0 0 1 18.5 6v3a1.5 1.5 0 0 1-1.5 1.5h-3A1.5 1.5 0 0 1 12.5 9V6A1.5 1.5 0 0 1 14 4.5m2.25 13h3.5a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 19.75 22h-3.5a1.75 1.75 0 0 1-1.75-1.75v-1a1.75 1.75 0 0 1 1.75-1.75m0 0v-1.25a1.75 1.75 0 0 1 3.5 0v1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pc8f15m6q {
  d: path("M2.5 2.5v19M14.886 13H3.75q-.061 0-.123-.006q-.061-.006-.121-.018t-.119-.03t-.115-.041t-.111-.053t-.105-.063t-.099-.073t-.091-.082q-.043-.044-.082-.091t-.073-.099t-.063-.105t-.053-.111q-.023-.056-.041-.115t-.03-.119t-.018-.121t-.006-.123t.006-.123t.018-.121t.03-.119t.041-.115q.024-.057.053-.111t.063-.105t.073-.099t.082-.091t.091-.082t.099-.073t.105-.063t.111-.053q.056-.023.115-.041t.119-.03t.121-.018t.123-.006h16.5q.061 0 .123.006q.061.006.121.018t.119.03t.115.041q.057.024.111.053t.105.063t.099.073t.091.082q.043.044.082.091t.073.099t.063.105t.053.111q.023.056.041.115t.03.119t.018.121t.006.123q0 .145-.033.286t-.098.271t-.157.242t-.209.199M2.5 18l5-5");
}

</style>
