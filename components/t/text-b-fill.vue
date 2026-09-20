<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="b0dsusb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:text-b-fill" /></template>
<style>
.b0dsusb9h {
  fill: currentColor;
  d: path("M168 156a20 20 0 0 1-20 20H96v-40h52a20 20 0 0 1 20 20m56-108v160a16 16 0 0 1-16 16H48a16 16 0 0 1-16-16V48a16 16 0 0 1 16-16h160a16 16 0 0 1 16 16m-40 108a36 36 0 0 0-18-31.15A36 36 0 0 0 140 64H88a8 8 0 0 0-8 8v112a8 8 0 0 0 8 8h60a36 36 0 0 0 36-36m-24-56a20 20 0 0 0-20-20H96v40h44a20 20 0 0 0 20-20");
}

</style>
