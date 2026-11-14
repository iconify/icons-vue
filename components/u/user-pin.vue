<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h1ug_pbap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:user-pin" /></template>
<style>
.h1ug_pbap {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.818 5.068Q4.5 6.386 4.5 8.25t1.318 3.182T9 12.75t3.182-1.318T13.5 8.25t-1.318-3.182T9 3.75T5.818 5.068m12.191 10.499Q14.75 12.742 14.75 10q0-3.75 3.75-3.75T22.25 10q0 2.742-3.259 5.567q-.051.044-.108.078q-.058.034-.121.058q-.063.023-.129.035t-.133.012t-.133-.012t-.129-.035t-.121-.058q-.057-.034-.108-.078M1.75 20q0-2.427 2.213-4.015Q6.03 14.5 9 14.5t5.037 1.485Q16.25 17.573 16.25 20q0 1.75-1.75 1.75h-11q-1.75 0-1.75-1.75");
}

</style>
