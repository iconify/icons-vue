<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aj6j0vbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mobile-optimized-32-filled" /></template>
<style>
.aj6j0vbkk {
  fill: currentColor;
  d: path("M6 2a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H3a1 1 0 0 1 0-2h2V3a1 1 0 0 1 1-1m20 0a1 1 0 0 1 1 1v2h2a1 1 0 1 1 0 2h-3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1M9 9a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H11a2 2 0 0 1-2-2zm4.5 3a1 1 0 1 0 0 2h5a1 1 0 1 0 0-2zm0 4a1 1 0 1 0 0 2h3a1 1 0 1 0 0-2zM7 29a1 1 0 1 1-2 0v-2H3a1 1 0 1 1 0-2h3a1 1 0 0 1 1 1zm20 0a1 1 0 1 1-2 0v-3a1 1 0 0 1 1-1h3a1 1 0 1 1 0 2h-2z");
}

</style>
