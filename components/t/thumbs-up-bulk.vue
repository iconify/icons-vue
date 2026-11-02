<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a_pcl8pjk"/><path class="lwj2ly6-e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-up-bulk" /></template>
<style>
.a_pcl8pjk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 9a3 3 0 0 0 3-3V5a3 3 0 1 1 6 0v3a.997.997 0 0 0 1 1h2a3 3 0 0 1 3 3v2a1 1 0 0 1-.051.316l-2 6c-.196.586-.66 1.031-1.203 1.302c-.541.271-1.145.382-1.746.382H9c-.74 0-1.45-.27-2-.764a3 3 0 0 1-3.225.502A3 3 0 0 1 2 19v-7a3 3 0 0 1 3-3Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.lwj2ly6-e {
  d: path("M8 10v9a3 3 0 1 1-6 0v-7a3 3 0 0 1 3-3h2a1 1 0 0 1 1 1m-2 1H5a.997.997 0 0 0-1 1v7a1 1 0 0 0 2 0Z");
}

</style>
