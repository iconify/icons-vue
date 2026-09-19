<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2g-wac0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-mark-chat-read" /></template>
<style>
.e2g-wac0l {
  fill: currentColor;
  d: path("M12.03 17.5c-.02.17-.03.33-.03.5H6l-4 4V2h20v8.68A6.995 6.995 0 0 0 12 17c0 .17.01.33.03.5M23 14.34l-1.41-1.41l-4.24 4.24l-2.12-2.12l-1.41 1.41L17.34 20z");
}

</style>
