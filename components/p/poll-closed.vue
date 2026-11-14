<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5n5tpn3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:poll-closed" /></template>
<style>
.f5n5tpn3n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 20.5V14m4 6.5V9m4 11.5v-17m3.5 12h7v6h-7Zm1.5 0V14a2 2 0 0 1 4 0v1.5");
}

</style>
