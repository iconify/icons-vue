<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7dmycjlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pharmacy-counter-sharp" /></template>
<style>
.h7dmycjlz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.4 3.25h1.7V5.4h2.15v2.2H13.1v2.15h-2.2V7.6H8.75V5.4h2.15V3.25zM4.25 10h3.5v3.5h-3.5zm12 1h3.5v2.5h-3.5zm-13.5 2.5h18.5v7.75H2.75zM6 17h12");
}

</style>
