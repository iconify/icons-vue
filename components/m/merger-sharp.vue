<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l872knbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:merger-sharp" /></template>
<style>
.l872knbto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h6v6h-6zm12.5 0h6v6h-6zm-9.5 8l3.5 3.5m0-2.75v2.75H6.5m11.75-3.5l-3.5 3.5m0-2.75v2.75h2.75m-9.25 1.5h7.5v5.5h-7.5z");
}

</style>
