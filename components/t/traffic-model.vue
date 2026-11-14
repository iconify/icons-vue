<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvk6wub2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:traffic-model" /></template>
<style>
.dvk6wub2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 13h13v5.5h-13ZM8 18.5V21m8-2.5V21m-8.5-8L9 9.5h6l1.5 3.5m-13-3l3-7.5m14 7.5l-3-7.5");
}

</style>
