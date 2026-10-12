<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhbn84bti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ticket-sharp" /></template>
<style>
.mhbn84bti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 7.75v-2h18.5V9.5a2.5 2.5 0 0 0 0 5v3.75H2.75V14.5a2.5 2.5 0 0 0 0-5Zm12.5 0v.75m0 3v1m0 3v.75");
}

</style>
