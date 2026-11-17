<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh3w-ab9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:socket-fill-sharp" /></template>
<style>
.wh3w-ab9g {
  fill: currentColor;
  d: path("M2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1m10-4a5 5 0 1 0-.001-10.001A5 5 0 0 0 12 17m-4-5a1.5 1.5 0 1 1 3.001.001A1.5 1.5 0 0 1 8 12m5 0a1.5 1.5 0 1 1 3.001.001A1.5 1.5 0 0 1 13 12");
}

</style>
