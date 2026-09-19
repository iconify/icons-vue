<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu_-64b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-crop-landscape" /></template>
<style>
.vu_-64b-b {
  fill: currentColor;
  d: path("M21 5H3v14h18zm-2 12H5V7h14z");
}

</style>
