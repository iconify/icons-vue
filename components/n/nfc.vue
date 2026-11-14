<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldytt4bbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:nfc" /></template>
<style>
.ldytt4bbz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.375 3h1.25A4.375 4.375 0 0 1 13 7.375v9.25A4.375 4.375 0 0 1 8.625 21h-1.25A4.375 4.375 0 0 1 3 16.625v-9.25A4.375 4.375 0 0 1 7.375 3M6.5 17.5h3m5.975-7.975a3.5 3.5 0 0 1 0 4.95M18.362 7.5a7 7 0 0 1 0 9");
}

</style>
