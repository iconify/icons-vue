<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6_v-ubkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:moth-repellent" /></template>
<style>
.k6_v-ubkh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 7C7 3 2.5 3.5 3 8c.5 3 3 3.5 5.5 3.75c-2.5 1.75-3 4.75-1 5.75C9 18 10.5 16 11 14Zm1.656 9.967c-.755-.676-1.37-1.821-1.656-2.967V7c4-4 8.5-3.5 8 1c-.5 3-3 3.5-5.5 3.75a5.7 5.7 0 0 1 1.626 1.706M8.5 3L11 7l2.5-4m1.75 15.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0m1 2.25l4.5-4.5");
}

</style>
