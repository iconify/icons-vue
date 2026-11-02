<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_myy07pe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-down-fill" /></template>
<style>
.h_myy07pe {
  fill: currentColor;
  d: path("M6 2.171V15H5a3 3 0 0 1-3-3V5a3 3 0 0 1 4-2.829m2 0A3 3 0 0 1 9 2h8c.601 0 1.205.111 1.746.382c.543.271 1.007.716 1.203 1.302l2 6A1 1 0 0 1 22 10v2a3 3 0 0 1-3 3h-2a.997.997 0 0 0-1 1v3a3 3 0 1 1-6 0v-1c0-1.27-.804-2.405-2-2.83Z");
}

</style>
