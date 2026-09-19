<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn3u90atg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-battery-0-bar" /></template>
<style>
.yn3u90atg {
  fill: currentColor;
  d: path("M17 5v16c0 .55-.45 1-1 1H8c-.55 0-1-.45-1-1V5c0-.55.45-1 1-1h2V3c0-.55.45-1 1-1h2c.55 0 1 .45 1 1v1h2c.55 0 1 .45 1 1m-2 1H9v14h6z");
}

</style>
