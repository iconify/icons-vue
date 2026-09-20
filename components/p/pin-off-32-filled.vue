<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ebrcilq2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pin-off-32-filled" /></template>
<style>
.ebrcilq2b {
  fill: currentColor;
  d: path("m20.187 21.601l8.106 8.106a1 1 0 0 0 1.414-1.414l-26-26a1 1 0 0 0-1.414 1.414l8.106 8.106l-3.68 1.226a2 2 0 0 0-.782 3.312l4.15 4.149L4 26.586V28h1.415l6.085-6.086l4.15 4.149a2 2 0 0 0 3.31-.782zm7.538-5.345l-5.29 2.644L13.1 9.565l2.645-5.29c1.22-2.442 4.475-2.97 6.406-1.04l6.613 6.615c1.93 1.93 1.403 5.185-1.04 6.406");
}

</style>
