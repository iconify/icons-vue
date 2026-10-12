<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="th999sluy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:radiator-car-sharp" /></template>
<style>
.th999sluy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 5.75h17V18.5h-17zm3.75 3v6.75m3.25-6.75v6.75m3.25-6.75v6.75M17 8.75v6.75m-6.5-9.75v-3h3v3m-7 12.75v2.75m11-2.75v2.75");
}

</style>
