<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxtdvmbvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:panorama-horizontal-sharp" /></template>
<style>
.rxtdvmbvh {
  fill: currentColor;
  d: path("M2.025 20.5V3.475q1.875.875 4.5 1.45t5.5.575t5.5-.575t4.5-1.45V20.5q-1.875-.875-4.5-1.437t-5.5-.563t-5.5.563t-4.5 1.437");
}

</style>
