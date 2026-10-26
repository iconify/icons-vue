<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ofwptnbhd"/><path class="pb8cp7bmi"/><path class="z1_y6ebxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:z-ai" /></template>
<style>
.ofwptnbhd {
  fill: var(--svg-color--fff, #fff);
  d: path("M256 39.956V216.15c-.1 22.005-18 39.85-40.034 39.85H39.942C17.875 256 0 238.119 0 216.044V39.956C0 17.881 17.875 0 39.942 0h176.116C238.125 0 256 17.881 256 39.956");
}

.pb8cp7bmi {
  fill: var(--svg-color--2d2d2d, #2d2d2d);
  d: path("M215.966 253.073H39.942c-20.453 0-37.019-16.572-37.019-37.032V39.955c0-20.46 16.566-37.032 37.019-37.032h176.116c20.453 0 37.019 16.572 37.019 37.032v176.179c-.093 20.367-16.659 36.94-37.111 36.94");
}

.z1_y6ebxf {
  fill: var(--svg-color--fff, #fff);
  d: path("M214.022 54.842L110.74 201.158H41.885L145.167 54.842zm-4.35 124.753v21.563h-86.068l12.124-17.213c1.85-2.684 4.997-4.35 8.329-4.35zM46.235 76.313V54.749l.443.012c6.641.08 85.625.08 85.625.08l-12.03 17.122c-1.852 2.684-4.998 4.35-8.33 4.35z");
}

</style>
