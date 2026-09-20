<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r7jhiy9fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:voicemail-20-filled" /></template>
<style>
.r7jhiy9fq {
  fill: currentColor;
  d: path("M6 10a1 1 0 1 1 2 0a1 1 0 0 1-2 0m6 0a1 1 0 1 1 2 0a1 1 0 0 1-2 0M2 6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2zm7 4a2 2 0 0 0-.268-1h2.536A2 2 0 1 0 13 8H7a2 2 0 1 0 2 2");
}

</style>
