<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jt9lt-til"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:regex-fill-round" /></template>
<style>
.jt9lt-til {
  fill: currentColor;
  d: path("M17 3v3l2.4-1.8a1 1 0 0 1 1.2 1.6L17.667 8l2.933 2.2a1 1 0 0 1-1.2 1.6L17 10v3a1 1 0 0 1-2 0v-3l-2.4 1.8a1 1 0 0 1-1.2-1.6L14.333 8L11.4 5.8a1 1 0 0 1 1.2-1.6L15 6V3a1 1 0 0 1 2 0M2 19a3 3 0 1 1 6 0a3 3 0 0 1-6 0m2 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
