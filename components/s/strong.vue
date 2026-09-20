<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wvobubbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:strong" /></template>
<style>
.wvobubbrb {
  fill: var(--svg-color--1668b0, #1668b0);
  fill-rule: evenodd;
  d: path("M21 12a9 9 0 1 1-18 0a9 9 0 0 1 18 0m-1.059 0A7.941 7.941 0 1 1 4.06 12a7.941 7.941 0 0 1 15.882 0m-5.974-5.294l3.327 2.489v.158H9.353V12h4.765v2.12H6.706V6.706zM9.882 9.882h7.412v7.412H9.991l-3.285-2.457v-.188h7.941v-3.178H9.882z");
}

</style>
