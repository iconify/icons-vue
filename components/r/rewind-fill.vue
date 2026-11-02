<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr8iscbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rewind-fill" /></template>
<style>
.cr8iscbuf {
  fill: currentColor;
  d: path("M13 8.5v.897l5.24-3.056A2.5 2.5 0 0 1 22 8.5v7a2.501 2.501 0 0 1-3.76 2.159L13 14.603v.897a2.501 2.501 0 0 1-3.76 2.159l-6-3.5a2.5 2.5 0 0 1 0-4.318l6-3.5A2.5 2.5 0 0 1 13 8.5");
}

</style>
