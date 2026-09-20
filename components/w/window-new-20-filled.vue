<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iz-49bbuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-new-20-filled" /></template>
<style>
.iz-49bbuk {
  fill: currentColor;
  d: path("M14 3a3 3 0 0 1 3 3v6a3 3 0 0 1-2.13 2.871A3 3 0 0 1 12 17H7.5A4.5 4.5 0 0 1 3 12.5V8a3 3 0 0 1 2.129-2.871A3 3 0 0 1 8 3zM5 6.27c-.598.346-1 .99-1 1.73v4.5A3.5 3.5 0 0 0 7.5 16H12c.74 0 1.383-.403 1.729-1H8a3 3 0 0 1-3-3zM9.5 6a.5.5 0 0 0 0 1h2.793l-4.147 4.147a.5.5 0 1 0 .708.707L13 7.707V10.5a.5.5 0 0 0 1 0v-4a.5.5 0 0 0-.5-.5z");
}

</style>
