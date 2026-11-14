<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exdp2nbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pos-age-check" /></template>
<style>
.exdp2nbvu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.2 12.5H2.5v-10H17v9.9m-8.25.1V19m2.45 2.5H4.5V19h6.7M5.5 6h5m-5 3.25H8m3 0h3m0 6h8v6.5h-8Zm2.5 3.25h.01m2.24-1H20m-1.25 2.25H20");
}

</style>
