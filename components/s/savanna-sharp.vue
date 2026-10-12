<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iq4yxgbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:savanna-sharp" /></template>
<style>
.iq4yxgbzb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 8.25c0-1.75 3.25-3 7.25-3s7.25 1.25 7.25 3V10H4.75zM12 10v8.25M12 14l-3-4m3 3l2.25-3m-11.5 8.25h18.5m-14.75 3h11");
}

</style>
