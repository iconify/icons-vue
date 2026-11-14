<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjf6x38jx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:perforating-gun" /></template>
<style>
.wjf6x38jx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 6.75h16l3 2.5l-3 2.5h-16Zm2.25 5L3 15.5m1.75-3.75v5.5m0-5.5L6.5 15.5m4.5-3.75L9.25 15.5M11 11.75v5.5m0-5.5l1.75 3.75m4.5-3.75L15.5 15.5m1.75-3.75v5.5m0-5.5L19 15.5");
}

</style>
