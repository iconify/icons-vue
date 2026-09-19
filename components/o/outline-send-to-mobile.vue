<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jybwwr5rf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-send-to-mobile" /></template>
<style>
.jybwwr5rf {
  fill: currentColor;
  d: path("m18 8l4 4l-4 4l-1.41-1.41L18.17 13H13v-2h5.17l-1.59-1.59zM7 1.01L17 1c1.1 0 2 .9 2 2v4h-2V6H7v12h10v-1h2v4c0 1.1-.9 2-2 2H7c-1.1 0-2-.9-2-2V3c0-1.1.9-1.99 2-1.99M7 21h10v-1H7zM7 4h10V3H7z");
}

</style>
