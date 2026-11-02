<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kgm-67b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:suv-fill" /></template>
<style>
.kgm-67b0f {
  fill: currentColor;
  d: path("M9.829 19a3 3 0 0 1-5.7-.128A3.005 3.005 0 0 1 2 16V8a3 3 0 0 1 3-3h8c.265 0 .52.105.707.293L17.414 9H19a3 3 0 0 1 3 3v4c0 1.32-.866 2.487-2.128 2.872a3 3 0 0 1-5.701.128ZM9 7H4.997A1 1 0 0 0 4 8v3h5Zm3.586 0H11v4h5.586ZM6.291 18.705l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

</style>
