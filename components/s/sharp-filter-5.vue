<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v620rgbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-filter-5" /></template>
<style>
.v620rgbbd {
  fill: currentColor;
  d: path("M23 1H5v18h18zm-2 16H7V3h14zM3 5H1v18h18v-2H3zm14 10V9h-4V7h4V5h-6v6h4v2h-4v2z");
}

</style>
