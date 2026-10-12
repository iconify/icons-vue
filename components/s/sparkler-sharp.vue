<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsuauubvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sparkler-sharp" /></template>
<style>
.qsuauubvd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 20.25L12 12m3-5.75l.33 2.42l2.42.33l-2.42.33l-.33 2.42l-.33-2.42L12.25 9l2.42-.33zm0-1.5V3m3.01 2.99l1.23-1.23M19.25 9H21m-2.99 3.01l1.23 1.23m-4.24.01V15m-4.25-6H9m2.99-3.01l-1.23-1.23");
}

</style>
