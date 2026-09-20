<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mku8rtb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tv-guide-outline-sharp" /></template>
<style>
.mku8rtb_t {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14V5H5zm0 0V5zm3-3h2v-6h1.75L14 16h2l3-8h-2.5L15 12.5L13.5 8H5v2h3z");
}

</style>
