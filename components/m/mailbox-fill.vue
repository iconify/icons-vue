<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dt5w9hqdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mailbox-fill" /></template>
<style>
.dt5w9hqdf {
  fill: currentColor;
  d: path("M18 8h1a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-7v-9a5.01 5.01 0 0 0-4-4.901V8h8V3a1 1 0 0 1 1-1h4a1 1 0 0 1 0 2h-3Zm-8 5v9H5a3 3 0 0 1-3-3v-6a5.01 5.01 0 0 1 4-4.901V9a1 1 0 0 0 1 1a3 3 0 0 1 3 3");
}

</style>
