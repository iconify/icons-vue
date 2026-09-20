<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wrr0rij1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:vibrate-light" /></template>
<style>
.wrr0rij1z {
  fill: currentColor;
  d: path("M160 34H96a22 22 0 0 0-22 22v144a22 22 0 0 0 22 22h64a22 22 0 0 0 22-22V56a22 22 0 0 0-22-22m10 166a10 10 0 0 1-10 10H96a10 10 0 0 1-10-10V56a10 10 0 0 1 10-10h64a10 10 0 0 1 10 10Zm44-112v80a6 6 0 0 1-12 0V88a6 6 0 0 1 12 0m32 16v48a6 6 0 0 1-12 0v-48a6 6 0 0 1 12 0M54 88v80a6 6 0 0 1-12 0V88a6 6 0 0 1 12 0m-32 16v48a6 6 0 0 1-12 0v-48a6 6 0 0 1 12 0");
}

</style>
