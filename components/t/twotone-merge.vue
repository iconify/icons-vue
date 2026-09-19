<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpjazun7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-merge" /></template>
<style>
.lpjazun7z {
  fill: currentColor;
  d: path("M6.41 21L5 19.59l4.83-4.83c.75-.75 1.17-1.77 1.17-2.83v-5.1L9.41 8.41L8 7l4-4l4 4l-1.41 1.41L13 6.83v5.1c0 1.06.42 2.08 1.17 2.83L19 19.59L17.59 21L12 15.41z");
}

</style>
