<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi2xc8bop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-present-to-all" /></template>
<style>
.hi2xc8bop {
  fill: currentColor;
  d: path("M23 3H1v18h22zm-2 16.02H3V4.98h18zM10 12H8l4-4l4 4h-2v4h-4z");
}

</style>
