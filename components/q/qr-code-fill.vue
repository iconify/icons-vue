<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc0613bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:qr-code-fill" /></template>
<style>
.jc0613bly {
  fill: currentColor;
  d: path("M3 5a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm10 0a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2ZM3 15a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Zm14-2a1 1 0 0 1 0 2h-3a1 1 0 0 1 0-2Zm3.01 0a1 1 0 0 1 0 2H20a1 1 0 0 1 0-2ZM13 20v-2a1 1 0 0 1 2 0v2a1 1 0 0 1-2 0m8-2v2a1 1 0 0 1-2 0v-1h-1a1 1 0 0 1 0-2h2a1 1 0 0 1 1 1");
}

</style>
