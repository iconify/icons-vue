<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm22hemnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-file-present" /></template>
<style>
.vm22hemnb {
  fill: currentColor;
  d: path("M14 2H4v20h16V8zm2 13c0 2.21-1.79 4-4 4s-4-1.79-4-4V9.5a2.5 2.5 0 0 1 5 0V15h-2V9.5c0-.28-.22-.5-.5-.5s-.5.22-.5.5V15c0 1.1.9 2 2 2s2-.9 2-2v-4h2zm-2-7V4l4 4z");
}

</style>
