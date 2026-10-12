<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scqojortg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pilgrim-staff-sharp" /></template>
<style>
.scqojortg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.25V6a2.5 2.5 0 0 1 5 0m-5 1.5l-5.5 2m0 0a1.25 1.25 0 0 1 .9 2.15l2.1.727V14.5a3 3 0 0 1-6 0v-2.123l2.1-.727a1.25 1.25 0 0 1 .9-2.15Z");
}

</style>
