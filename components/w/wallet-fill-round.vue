<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgmo6izin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wallet-fill-round" /></template>
<style>
.pgmo6izin {
  fill: currentColor;
  d: path("M22 8h-4a4 4 0 0 0 0 8h4a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H7a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5m-4 6a2 2 0 1 1 0-4h4v4Zm0-3a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
