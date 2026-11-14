<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fsjmidbre"/><path class="iiown5zbm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:property-broker" /></template>
<style>
.fsjmidbre {
  d: path("M3.75 5zA1.25 1.25 0 0 1 5 6.25v5.5A1.25 1.25 0 0 1 3.75 13a1.25 1.25 0 0 1-1.25-1.25v-5.5A1.25 1.25 0 0 1 3.75 5m15.632 7.65q-.09-.088-.162-.191q-.071-.104-.12-.22q-.05-.116-.075-.24T19 11.75v-5.5q0-.061.006-.123q.006-.061.018-.121t.03-.119t.041-.115q.024-.057.053-.111t.063-.105t.073-.099t.082-.091q.044-.043.091-.082t.099-.073q.051-.034.105-.063t.111-.053t.115-.041t.119-.03q.06-.012.121-.018Q20.189 5 20.25 5t.123.006q.061.006.121.018t.119.03t.115.041q.057.024.111.053t.105.063t.099.073t.091.082t.082.091t.073.099t.063.105t.053.111q.023.056.041.115t.03.119t.018.121q.006.062.006.123v5.5q0 .233-.084.45M19 6.5h-3.5L11 10c-.75.6-.5 1.75.5 1.75h1L15 10M5 6.5h3L10.25 8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iiown5zbm {
  d: path("M5 11.5L9 15c.5.5 1.25.5 1.75 0l3.5-3H19m-4 9l6-6m-5.5.5h.01m4.99 5h.01");
}

</style>
