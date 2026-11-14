<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tuatqcbtp"/><path class="lt7__db2t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:quarantine-shelf" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lt7__db2t {
  d: path("M8.75 2.5h6a1.75 1.75 0 0 1 1.75 1.75v4.5a1.75 1.75 0 0 1-1.75 1.75h-6A1.75 1.75 0 0 1 7 8.75v-4.5A1.75 1.75 0 0 1 8.75 2.5m1.75 0v3m2.5-3v3M14.25 18a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M16 18h4");
}

.tuatqcbtp {
  d: path("M2.5 2.5v19M13.786 13H3.75q-.061 0-.123-.006q-.061-.006-.121-.018t-.119-.03t-.115-.041t-.111-.053t-.105-.063t-.099-.073t-.091-.082q-.043-.044-.082-.091t-.073-.099t-.063-.105t-.053-.111q-.023-.056-.041-.115t-.03-.119t-.018-.121t-.006-.123t.006-.123t.018-.121t.03-.119t.041-.115q.024-.057.053-.111t.063-.105t.073-.099t.082-.091t.091-.082t.099-.073t.105-.063t.111-.053q.056-.023.115-.041t.119-.03t.121-.018t.123-.006h16.5q.061 0 .123.006q.061.006.121.018t.119.03t.115.041q.057.024.111.053t.105.063t.099.073t.091.082q.043.044.082.091t.073.099t.063.105t.053.111q.023.056.041.115t.03.119t.018.121t.006.123q0 .292-.129.554M2.5 18l5-5");
}

</style>
