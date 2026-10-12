<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gupglzs0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:plug-puzzle-20-regular" /></template>
<style>
.gupglzs0z {
  fill: currentColor;
  d: path("M3 13.73a.73.73 0 0 1 .73-.73H4a2 2 0 1 0 0-4h-.27A.73.73 0 0 1 3 8.27V7a3 3 0 0 1 3-3h1.5a.5.5 0 0 1 0 1H6a2 2 0 0 0-2 2v1a3 3 0 0 1 0 6v1a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2v-3h-.5A3.5 3.5 0 0 1 10 8.5v-2A1.5 1.5 0 0 1 11.5 5h.5V3.5a.5.5 0 0 1 1 0V5h2V3.5a.5.5 0 0 1 1 0V5h.5A1.5 1.5 0 0 1 18 6.5v2a3.5 3.5 0 0 1-3 3.464V15a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3zm8-5.23a2.5 2.5 0 0 0 2.5 2.5h1A2.5 2.5 0 0 0 17 8.5v-2a.5.5 0 0 0-.5-.5h-5a.5.5 0 0 0-.5.5z");
}

</style>
