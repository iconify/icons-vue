<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0vosibor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toaster-fill-sharp" /></template>
<style>
.p0vosibor {
  fill: currentColor;
  d: path("M5 8V5a3 3 0 1 1 6 0v3h2V5a3 3 0 1 1 6 0v3h2a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V9a1 1 0 0 1 1-1Zm4-3a1 1 0 0 0-2 0v3h2Zm8 0a1 1 0 0 0-2 0v3h2Zm1 8a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0Z");
}

</style>
