<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rewx-801w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-format-strikethrough" /></template>
<style>
.rewx-801w {
  fill: currentColor;
  d: path("M3 12h18v2H3zm11-2V7h5V4H5v3h5v3zm-4 6h4v3h-4z");
}

</style>
