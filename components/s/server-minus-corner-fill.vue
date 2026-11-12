<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azcpo-b5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-minus-corner-fill" /></template>
<style>
.azcpo-b5y {
  fill: currentColor;
  d: path("M5 3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3m2.01 3H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M9 21H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3h4a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1m12-6a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2ZM7.01 16H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
