<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5tv2rb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-power" /></template>
<style>
.w5tv2rb9u {
  fill: currentColor;
  d: path("M16 9v4.66l-3.5 3.51V19h-1v-1.83L8 13.65V9zm0-6h-2v4h-4V3H8v4h-.01C6.9 6.99 6 7.89 6 8.98v5.52L9.5 18v3h5v-3l3.5-3.51V9c0-1.1-.9-2-2-2z");
}

</style>
