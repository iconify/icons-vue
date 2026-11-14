<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzdr6fb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tax-office-pin" /></template>
<style>
.uzdr6fb2r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 19c-4-3.5-7-6.5-7-10a7 7 0 0 1 14 0c0 3.5-3 6.5-7 10Zm-6 2.75h12M14.5 6.5l-5 5m0-4.5h.01m4.99 4h.01");
}

</style>
