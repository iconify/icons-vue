<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0htw__0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-cursor-bulk" /></template>
<style>
.v0htw__0u {
  fill: currentColor;
  d: path("M10 2c.74 0 1.45.27 2 .764A3 3 0 0 1 14 2h2a1 1 0 0 1 0 2h-2a.997.997 0 0 0-1 1v14a1 1 0 0 0 1 1h2a1 1 0 0 1 0 2h-2c-.74 0-1.45-.27-2-.764A3 3 0 0 1 10 22H8a1 1 0 0 1 0-2h2a1 1 0 0 0 1-1V5a.997.997 0 0 0-1-1H8a1 1 0 0 1 0-2Z");
}

</style>
