<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jj7r8vyvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-file-present" /></template>
<style>
.jj7r8vyvl {
  fill: currentColor;
  d: path("M14 2H6c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V8zm4 18H6V4h8v4h4zm-6-3c-1.1 0-2-.9-2-2V9.5c0-.28.22-.5.5-.5s.5.22.5.5V15h2V9.5a2.5 2.5 0 0 0-5 0V15c0 2.21 1.79 4 4 4s4-1.79 4-4v-4h-2v4c0 1.1-.9 2-2 2");
}

</style>
