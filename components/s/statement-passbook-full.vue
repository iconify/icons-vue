<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyf1grjps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:statement-passbook-full" /></template>
<style>
.eyf1grjps {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4H15v17.5H2.5ZM15 5.5h2.25V20H15m2.25-13h2.25v11.5h-2.25m2.25-10h2.25V17H19.5M6 4v17.5m3-13h3.5");
}

</style>
