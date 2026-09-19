<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tatwfnbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-music-video" /></template>
<style>
.tatwfnbel {
  fill: currentColor;
  d: path("M23 3H1v18h22zm-2 16H3V5h18zM8 15c0-1.66 1.34-3 3-3c.35 0 .69.07 1 .18V6h5v2h-3v7.03A3.003 3.003 0 0 1 11 18c-1.66 0-3-1.34-3-3");
}

</style>
