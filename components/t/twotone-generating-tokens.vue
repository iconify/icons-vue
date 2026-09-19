<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x-100ybsh"/><path class="hcs__ntbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-generating-tokens" /></template>
<style>
.hcs__ntbn {
  fill: currentColor;
  d: path("M9 4c-4.42 0-8 3.58-8 8s3.58 8 8 8s8-3.58 8-8s-3.58-8-8-8m0 14c-3.31 0-6-2.69-6-6s2.69-6 6-6s6 2.69 6 6s-2.69 6-6 6m3-7.5h-2v5H8v-5H6V9h6zm8.25-6.75L23 5l-2.75 1.25L19 9l-1.25-2.75L15 5l2.75-1.25L19 1zm0 14L23 19l-2.75 1.25L19 23l-1.25-2.75L15 19l2.75-1.25L19 15z");
}

.x-100ybsh {
  fill: currentColor;
  d: path("M9 6c-3.31 0-6 2.69-6 6s2.69 6 6 6s6-2.69 6-6s-2.69-6-6-6m3 4.5h-2v5H8v-5H6V9h6z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
