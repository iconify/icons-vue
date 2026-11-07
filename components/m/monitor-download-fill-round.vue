<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9u8p8wcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-download-fill-round" /></template>
<style>
.u9u8p8wcq {
  fill: currentColor;
  d: path("M8 3h8a5 5 0 0 1 5 5v5a5 5 0 0 1-5 5H8a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5m3.293 11.707a1 1 0 0 0 1.414 0l3-3a.999.999 0 1 0-1.414-1.414L13 11.586V7a1 1 0 0 0-2 0v4.586l-1.293-1.293a.999.999 0 1 0-1.414 1.414ZM9 19h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

</style>
