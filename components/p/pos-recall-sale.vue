<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp2jctl1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pos-recall-sale" /></template>
<style>
.vp2jctl1k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.2 12.5H2.5v-10H17v9.9m-8.25.1V19m3.45 2.5H4.5V19h7.7M5.5 6h5m-5 3.25H8m3 0h3m1 5.25l6.5 3.5l-6.5 3.5Z");
}

</style>
