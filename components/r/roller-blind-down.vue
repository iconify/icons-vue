<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxribfuyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:roller-blind-down" /></template>
<style>
.vxribfuyh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5h17v3h-17Zm1 3v13h8.1m6.9-6.8V5.5m-7.5 13v3m7-7V21m-2.75-2.75L18 21l2.75-2.75");
}

</style>
