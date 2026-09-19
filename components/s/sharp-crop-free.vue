<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-5jqgbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-crop-free" /></template>
<style>
.y-5jqgbhe {
  fill: currentColor;
  d: path("M3 3v6h2V5h4V3zm2 12H3v6h6v-2H5zm14 4h-4v2h6v-6h-2zm2-16h-6v2h4v4h2z");
}

</style>
