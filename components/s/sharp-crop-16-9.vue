<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r8cs0naer"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-crop-16-9" /></template>
<style>
.r8cs0naer {
  fill: currentColor;
  d: path("M21 7H3v10h18zm-2 8H5V9h14z");
}

</style>
