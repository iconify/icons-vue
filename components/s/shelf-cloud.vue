<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo29iobaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shelf-cloud" /></template>
<style>
.wo29iobaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 13h12a3.5 3.5 0 0 0 0-7A5.5 5.5 0 0 0 7.75 7A3.25 3.25 0 0 0 6 13Zm1 0a2.5 2.5 0 1 0 2.25 3.75M2.5 21h19");
}

</style>
