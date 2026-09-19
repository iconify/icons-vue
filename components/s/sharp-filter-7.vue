<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3xvwy7xh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-filter-7" /></template>
<style>
.g3xvwy7xh {
  fill: currentColor;
  d: path("M3 5H1v18h18v-2H3zm20-4H5v18h18zm-2 16H7V3h14zm-8-2l4-8V5h-6v2h4l-4 8z");
}

</style>
