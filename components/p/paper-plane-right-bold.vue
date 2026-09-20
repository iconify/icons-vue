<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lgim8jb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:paper-plane-right-bold" /></template>
<style>
.lgim8jb7z {
  fill: currentColor;
  d: path("M233.86 110.48L65.8 14.58a20 20 0 0 0-28.65 24.06L67.33 128l-30.18 89.36A20 20 0 0 0 56 244a20.1 20.1 0 0 0 9.81-2.58l.09-.06l168-96.07a20 20 0 0 0 0-34.81ZM63.19 215.26L88.61 140H144a12 12 0 0 0 0-24H88.61L63.18 40.72l152.76 87.17Z");
}

</style>
