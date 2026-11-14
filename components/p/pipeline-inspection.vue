<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdpk0mbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pipeline-inspection" /></template>
<style>
.tdpk0mbbz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 3.5zA1.25 1.25 0 0 1 5 4.75v7.5a1.25 1.25 0 0 1-1.25 1.25a1.25 1.25 0 0 1-1.25-1.25v-7.5A1.25 1.25 0 0 1 3.75 3.5m15.323 9.17Q19 12.466 19 12.25v-7.5q0-.061.006-.123q.006-.061.018-.121t.03-.119t.041-.115q.024-.057.053-.111t.063-.105t.073-.099t.082-.091q.044-.043.091-.082t.099-.073q.051-.034.105-.063t.111-.053t.115-.041t.119-.03t.121-.018q.062-.006.123-.006t.123.006q.061.006.121.018t.119.03t.115.041t.111.053t.105.063q.052.034.099.073t.091.082q.043.044.082.091t.073.099q.034.051.063.105t.053.111q.023.056.041.115t.03.119t.018.121t.006.123v7.5q0 .108-.018.214q-.019.106-.055.207q-.036.102-.09.195q-.053.094-.121.177q-.068.084-.15.154t-.174.126t-.193.094t-.206.059M5 5.5h14m-14 6h14m-3.75 6a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m4 1.75L21 21");
}

</style>
