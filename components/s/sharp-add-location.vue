<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e6ij6tr3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-add-location" /></template>
<style>
.e6ij6tr3j {
  fill: currentColor;
  d: path("M13 6h-2v3H8v2h3v3h2v-3h3V9h-3zm-1-4c4.2 0 8 3.22 8 8.2c0 3.32-2.67 7.25-8 11.8c-5.33-4.55-8-8.48-8-11.8C4 5.22 7.8 2 12 2");
}

</style>
