<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnob25r9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-play-arrow" /></template>
<style>
.vnob25r9m {
  fill: currentColor;
  d: path("M8 5v14l11-7z");
}

</style>
