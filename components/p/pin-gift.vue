<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az87eib8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-gift" /></template>
<style>
.az87eib8k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 7.5h18V12H3ZM4.75 12v7.75A1.25 1.25 0 0 0 6 21h12a1.25 1.25 0 0 0 1.25-1.25V12M12 7.5V21m0-13.5C11 4.5 9.5 3 8 3S6.25 4.5 7 5.5c1 1.25 3 2 5 2Zm0 0c1-3 2.5-4.5 4-4.5s1.75 1.5 1 2.5c-1 1.25-3 2-5 2Z");
}

</style>
