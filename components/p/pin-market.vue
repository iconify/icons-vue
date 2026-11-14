<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c3ak65hfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-market" /></template>
<style>
.c3ak65hfq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3 8l1.5-5h15L21 8a2.25 2.25 0 0 1-4.5 0A2.25 2.25 0 0 1 12 8a2.25 2.25 0 0 1-4.5 0A2.25 2.25 0 0 1 3 8Zm2.25 2.25V21.5m13.5-11.25V21.5M3 15.5h18");
}

</style>
