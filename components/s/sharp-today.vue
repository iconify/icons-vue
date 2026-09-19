<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgg3lzb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-today" /></template>
<style>
.bgg3lzb8l {
  fill: currentColor;
  d: path("M21 3h-3V1h-2v2H8V1H6v2H3v18h18zm-2 16H5V8h14zM7 10h5v5H7z");
}

</style>
