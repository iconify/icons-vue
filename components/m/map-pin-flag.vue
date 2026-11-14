<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhw2imtwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:map-pin-flag" /></template>
<style>
.lhw2imtwe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 21.5s-5-4-5-7.5a5 5 0 0 1 10 0c0 3.5-5 7.5-5 7.5Zm0-7.5h.01M17 2.5V12m0-9.5h4.5l-1.25 2.25L21.5 7H17Z");
}

</style>
