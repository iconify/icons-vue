<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qh4k2on2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tunnel-fill" /></template>
<style>
.qh4k2on2q {
  fill: currentColor;
  d: path("M11 2.049v6.076c-.362.094-.71.238-1.033.428L5.671 4.256A10 10 0 0 1 11 2.049m7.329 2.207l-4.296 4.297A4 4 0 0 0 13 8.125V2.049a10 10 0 0 1 5.329 2.207M21.801 10h-6.335l-.019-.033l4.297-4.296A10 10 0 0 1 21.801 10M2.199 10a10 10 0 0 1 2.057-4.329l4.297 4.296l-.019.033ZM2 15v-3h6v3Zm14-3h6v3h-6Zm-8 5v2a3 3 0 1 1-6 0v-2Zm14 0v2a3 3 0 1 1-6 0v-2Z");
}

</style>
