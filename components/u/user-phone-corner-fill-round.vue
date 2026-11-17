<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn34bjo6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-phone-corner-fill-round" /></template>
<style>
.qn34bjo6x {
  fill: currentColor;
  d: path("M4 7a5 5 0 1 1 10.001.001A5 5 0 0 1 4 7m6 8v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1c0-1.862.731-3.636 2.05-4.95a6.9 6.9 0 0 1 2.225-1.499A6.9 6.9 0 0 1 9 14a1 1 0 0 1 1 1m6.293 1.707l-.27-.27a4.01 4.01 0 0 0 3.54 3.54l-.27-.27a.999.999 0 1 1 1.414-1.414l1 1A1 1 0 0 1 22 20v1a1 1 0 0 1-1 1h-1a6 6 0 0 1-6-6v-1a1 1 0 0 1 1-1h1c.265 0 .52.105.707.293l1 1a.999.999 0 1 1-1.414 1.414");
}

</style>
