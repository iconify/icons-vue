<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyv7wnbpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skyscraper-fill-sharp" /></template>
<style>
.lyv7wnbpi {
  fill: currentColor;
  d: path("M9 4V3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v1h1a1 1 0 0 1 1 1v15h4a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h4V5a1 1 0 0 1 1-1Zm3 3a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm0 4a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm.01 4H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
