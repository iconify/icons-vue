<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d_3rkep4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shelf-ready-packaging" /></template>
<style>
.d_3rkep4a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 15h19v6.5h-19Zm2 0V9.5l1-1v-2h2v2l1 1V15m1.5 0V9.5l1-1v-2h2v2l1 1V15m1.5 0V9.5l1-1v-2h2v2l1 1V15M5.5 4.5h2m3.5 0h2m3.5 0h2M2.5 18h19");
}

</style>
