<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j-n0vnxfs"/><path class="cf28hclcm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:voicemail-bulk" /></template>
<style>
.cf28hclcm {
  d: path("M6 14h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.j-n0vnxfs {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12a4 4 0 1 1 8 0a4 4 0 0 1-8 0m12 0a4 4 0 1 1 8 0a4 4 0 0 1-8 0");
}

</style>
