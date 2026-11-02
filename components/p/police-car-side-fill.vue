<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_gs2nbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:police-car-side-fill" /></template>
<style>
.g_gs2nbmz {
  fill: currentColor;
  d: path("M6 3a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Zm10 0a1 1 0 0 1 0 2h-1a1 1 0 0 1 0-2ZM8 6.176V5a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v1.176c.649.226 1.224.634 1.707 1.117L18.414 11H19a3 3 0 0 1 3 3v2c0 1.32-.866 2.487-2.128 2.872a3 3 0 0 1-5.701.128H9.829a3 3 0 0 1-5.7-.128A3.005 3.005 0 0 1 2 16v-4c0-.265.105-.52.293-.707l4-4C6.776 6.81 7.351 6.402 8 6.176M8.828 8a1 1 0 0 0-.707.293L4 12.414V13h5V8ZM11 13h6.586l-4.707-4.707A1 1 0 0 0 12.172 8H11Zm-4.709 5.705l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

</style>
