<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enkysybih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paper-plane-clock-corner-fill" /></template>
<style>
.enkysybih {
  fill: currentColor;
  d: path("M11.684 2.051a1.001 1.001 0 0 1 1.265 1.265l-3 9a1 1 0 0 1-1.843.131l-1.38-2.759l1.981-1.981a.999.999 0 1 0-1.414-1.414L5.312 8.274l-2.759-1.38a1 1 0 0 1 .131-1.843ZM11 17a6 6 0 1 1 12 0a6 6 0 0 1-12 0m2 0a4 4 0 1 0 8 0a4 4 0 0 0-8 0m5-2v1h1a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0");
}

</style>
