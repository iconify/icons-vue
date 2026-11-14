<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps2nrym_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pos-recall-sale" /></template>
<style>
.ps2nrym_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5h7.5A3.5 3.5 0 0 1 17 6v3a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 9V6A3.5 3.5 0 0 1 6 2.5m2.75 10V19m3.926 2.09q-.088.097-.194.173q-.106.077-.226.13q-.119.053-.247.08t-.259.027h-6q-.061 0-.123-.006q-.061-.006-.121-.018t-.119-.03t-.115-.041q-.057-.024-.111-.053t-.105-.063t-.099-.073t-.091-.082q-.043-.044-.082-.091t-.073-.099q-.034-.051-.063-.105t-.053-.111t-.041-.115t-.03-.119q-.012-.06-.018-.121q-.006-.062-.006-.123t.006-.123q.006-.061.018-.121t.03-.119t.041-.115q.024-.057.053-.111t.063-.105t.073-.099t.082-.091t.091-.082t.099-.073t.105-.063t.111-.053q.056-.023.115-.041t.119-.03t.121-.018T5.75 19h6q.214 0 .416.071M5.5 6h5m-5 3.25H8m3 0h3m3.211 6.441l1.836.988a1.5 1.5 0 0 1 0 2.642l-1.836.988A1.5 1.5 0 0 1 15 18.989v-1.978a1.5 1.5 0 0 1 2.211-1.32");
}

</style>
