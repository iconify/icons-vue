<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srhx6kbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pos-login" /></template>
<style>
.srhx6kbzs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.1 12.5H2.5v-10H17v9.2m-8.25.8V19M13 20.8v.7H4.5V19h6.7M5.5 6h5m-5 3.25H8m3 0h3m5 5.25h2.75v7H19M14 18h4.5m-2-2l2 2l-2 2");
}

</style>
