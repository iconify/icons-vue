<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwzgajbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-speaker-notes-off" /></template>
<style>
.fwzgajbhz {
  fill: currentColor;
  d: path("M1.27 1.73L0 3l2.01 2.01L2 22l4-4h9l5.73 5.73L22 22.46zM8 14H6v-2h2zm-2-3V9l2 2zm16-9H4.08L10 7.92V6h8v2h-7.92l1 1H18v2h-4.92l6.99 6.99H22z");
}

</style>
