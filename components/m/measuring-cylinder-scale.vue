<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zuamtv6kv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:measuring-cylinder-scale" /></template>
<style>
.zuamtv6kv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 2.5h1.5v16h7v-16H17m-8.5 16l-2.5 3h12l-2.5-3m-7-12h3m-3 3.5h3m-3 3.5h7");
}

</style>
