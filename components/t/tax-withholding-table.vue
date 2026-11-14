<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5xxsmb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tax-withholding-table" /></template>
<style>
.o5xxsmb3t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.6 18.5H2.5v-16h18v9.2m-18-4.2h18m-9 0v10.6m6.5-3.6V21m-2.75-2.75L18 21l2.75-2.75");
}

</style>
