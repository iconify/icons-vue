<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkvvc5bqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:monument-sharp" /></template>
<style>
.vkvvc5bqj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 21.25V5.5h16.5v15.75h-4.5V16a3.75 3.75 0 0 0-7.5 0v5.25ZM3.75 9h16.5M2.75 3h18.5");
}

</style>
