<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="u-o9-gy6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:not-subset-of-thin" /></template>
<style>
.u-o9-gy6x {
  fill: currentColor;
  d: path("M210.69 37a4 4 0 0 0-5.65.27L199 44h-71a84 84 0 0 0-59.37 143.36L45 213.31a4 4 0 1 0 6 5.38l23.58-25.94A83.64 83.64 0 0 0 128 212h72a4 4 0 0 0 0-8h-72a75.66 75.66 0 0 1-48.07-17.18L211 42.69a4 4 0 0 0-.31-5.69M52 128a76.08 76.08 0 0 1 76-76h63.69L74 181.43A75.75 75.75 0 0 1 52 128");
}

</style>
