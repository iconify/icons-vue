<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq26xmx5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sailor-hat-sharp" /></template>
<style>
.dq26xmx5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 15.5V12a7 7 0 0 1 14 0v3.5ZM5 13h14m0 0l2.25-1.75M19 13l2.25 2.5M2.75 18h18.5v2.5H2.75z");
}

</style>
