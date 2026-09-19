<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt6rfkbkm"/><path class="h-cbelffk"/><path class="qby4mbagi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-file-present" /></template>
<style>
.h-cbelffk {
  fill: currentColor;
  d: path("M14 15c0 1.1-.9 2-2 2s-2-.9-2-2V9.5c0-.28.22-.5.5-.5s.5.22.5.5V15h2V9.5a2.5 2.5 0 0 0-5 0V15c0 2.21 1.79 4 4 4s4-1.79 4-4v-4h-2z");
}

.qby4mbagi {
  fill: currentColor;
  d: path("M14 2H6c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V8zm4 18H6V4h8v4h4z");
}

.tt6rfkbkm {
  fill: currentColor;
  d: path("M14 4H6v16h12V8h-4zm2 7v4c0 2.21-1.79 4-4 4s-4-1.79-4-4V9.5a2.5 2.5 0 0 1 5 0V15h-2V9.5c0-.28-.22-.5-.5-.5s-.5.22-.5.5V15c0 1.1.9 2 2 2s2-.9 2-2v-4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
