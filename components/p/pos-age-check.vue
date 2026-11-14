<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqogpqbey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pos-age-check" /></template>
<style>
.dqogpqbey {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5h7.5A3.5 3.5 0 0 1 17 6v3a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 9V6A3.5 3.5 0 0 1 6 2.5m2.75 10V19m2.736 2.5H5.75q-.061 0-.123-.006q-.061-.006-.121-.018t-.119-.03t-.115-.041q-.057-.024-.111-.053t-.105-.063t-.099-.073t-.091-.082q-.043-.044-.082-.091t-.073-.099q-.034-.051-.063-.105t-.053-.111t-.041-.115t-.03-.119q-.012-.06-.018-.121q-.006-.062-.006-.123t.006-.123q.006-.061.018-.121t.03-.119t.041-.115q.024-.057.053-.111t.063-.105t.073-.099t.082-.091t.091-.082t.099-.073t.105-.063t.111-.053q.056-.023.115-.041t.119-.03t.121-.018T5.75 19h5.4M5.5 6h5m-5 3.25H8m3 0h3m1.75 6h4.5A1.75 1.75 0 0 1 22 17v3a1.75 1.75 0 0 1-1.75 1.75h-4.5A1.75 1.75 0 0 1 14 20v-3a1.75 1.75 0 0 1 1.75-1.75m.75 3.25h.01m2.24-1H20m-1.25 2.25H20");
}

</style>
