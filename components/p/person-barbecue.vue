<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ldcg37hqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:person-barbecue" /></template>
<style>
.ldcg37hqk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.572 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c1.074 0 2.085.144 2.995.411M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm11 10.5l-3.25 3.25m4.146-7.328l3.182 3.182l-2.474 2.474l-3.182-3.182Z");
}

</style>
