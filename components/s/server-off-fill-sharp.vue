<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="def1h3dlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-off-fill-sharp" /></template>
<style>
.def1h3dlq {
  fill: currentColor;
  d: path("m2.707 1.293l20 20a.999.999 0 1 1-1.414 1.414L19.586 21H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h8.586l-2-2H3a1 1 0 0 1-1-1V4c0-.164.04-.325.117-.469l-.824-.824a.999.999 0 1 1 1.414-1.414M7.243 3H21a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-5.757ZM22 17.757L17.243 13H21a1 1 0 0 1 1 1ZM7.01 16H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
