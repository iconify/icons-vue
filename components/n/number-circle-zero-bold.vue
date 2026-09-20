<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="p-iuq7byw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:number-circle-zero-bold" /></template>
<style>
.p-iuq7byw {
  fill: currentColor;
  d: path("M128 20a108 108 0 1 0 108 108A108.12 108.12 0 0 0 128 20m0 192a84 84 0 1 1 84-84a84.09 84.09 0 0 1-84 84m0-144c-28.26 0-48 24.67-48 60s19.74 60 48 60s48-24.67 48-60s-19.74-60-48-60m0 96c-23.33 0-24-32.32-24-36s.67-36 24-36s24 32.32 24 36s-.67 36-24 36");
}

</style>
