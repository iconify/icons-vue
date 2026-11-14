<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nca-bcc_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tooth-post" /></template>
<style>
.nca-bcc_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 10H7V6c0-2 1-3 2.5-3c1 0 1.5.5 2.5.5s1.5-.5 2.5-.5C16 3 17 4 17 6v4h4.5M7 10l2.75 9.5c.5 2 4 2 4.5 0L17 10m-5-3.5v10");
}

</style>
