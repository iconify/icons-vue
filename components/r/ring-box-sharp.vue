<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxno7m24k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ring-box-sharp" /></template>
<style>
.rxno7m24k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 15.25v-12m14.5 12v-12m-14.5 3h14.5m-14.5 3h14.5m-14.5 3h14.5m-16.5 3h18.5v5.5H2.75zM6 18h12");
}

</style>
