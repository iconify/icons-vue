<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck8wqu08j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-mark-chat-read" /></template>
<style>
.ck8wqu08j {
  fill: currentColor;
  d: path("M12 18H6l-4 4V4c0-1.1.9-2 2-2h16c1.1 0 2 .9 2 2v7h-2V4H4v12h8zm11-3.66l-1.41-1.41l-4.24 4.24l-2.12-2.12l-1.41 1.41L17.34 20z");
}

</style>
