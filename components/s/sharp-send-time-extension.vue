<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyjc2tn7p"/><path class="lx745ynqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-send-time-extension" /></template>
<style>
.lx745ynqo {
  fill: currentColor;
  d: path("M13 12v4l4 1l-4 1v4l10-5z");
}

.qyjc2tn7p {
  fill: currentColor;
  d: path("M20 4h-6a2.5 2.5 0 0 0-5 0H3.01v5.8C5.7 9.8 6 11.96 6 12.5s-.29 2.7-3 2.7V21h5.8c0-2.16 1.37-2.78 2.2-2.94v-9.3l9 4.5z");
}

</style>
