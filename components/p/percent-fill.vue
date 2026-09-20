<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vm9lo0b0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:percent-fill" /></template>
<style>
.vm9lo0b0v {
  fill: currentColor;
  d: path("M176 172a12 12 0 1 1-12-12a12 12 0 0 1 12 12M92 96a12 12 0 1 0-12-12a12 12 0 0 0 12 12m132-48v160a16 16 0 0 1-16 16H48a16 16 0 0 1-16-16V48a16 16 0 0 1 16-16h160a16 16 0 0 1 16 16M64 84a28 28 0 1 0 28-28a28 28 0 0 0-28 28m128 88a28 28 0 1 0-28 28a28 28 0 0 0 28-28m-2.34-105.66a8 8 0 0 0-11.32 0l-112 112a8 8 0 0 0 11.32 11.32l112-112a8 8 0 0 0 0-11.32");
}

</style>
