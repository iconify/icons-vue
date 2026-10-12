<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-33n-bfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:takht-sharp" /></template>
<style>
.l-33n-bfl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 11h18.5v3H2.75zm1.75 3h3v7h-3v-1.25Zm12 0h3v7h-3v-1.25Zm-12-6.75h9V11h-9z");
}

</style>
