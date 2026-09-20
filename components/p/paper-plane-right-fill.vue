<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="c_0f1dbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:paper-plane-right-fill" /></template>
<style>
.c_0f1dbcp {
  fill: currentColor;
  d: path("M240 127.89a16 16 0 0 1-8.18 14L63.9 237.9A16.15 16.15 0 0 1 56 240a16 16 0 0 1-15-21.33l27-79.95a4 4 0 0 1 3.72-2.72H144a8 8 0 0 0 8-8.53a8.19 8.19 0 0 0-8.26-7.47h-72a4 4 0 0 1-3.79-2.72l-27-79.94a16 16 0 0 1 22.89-19.27l168 95.89a16 16 0 0 1 8.16 13.93");
}

</style>
