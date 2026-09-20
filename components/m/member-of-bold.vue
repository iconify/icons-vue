<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q-6mfvn8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:member-of-bold" /></template>
<style>
.q-6mfvn8l {
  fill: currentColor;
  d: path("M200 140H61.08A68.1 68.1 0 0 0 128 196h72a12 12 0 0 1 0 24h-72a92 92 0 0 1 0-184h72a12 12 0 0 1 0 24h-72a68.1 68.1 0 0 0-66.92 56H200a12 12 0 0 1 0 24");
}

</style>
