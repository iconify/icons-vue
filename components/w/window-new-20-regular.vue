<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lr_22q2ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-new-20-regular" /></template>
<style>
.lr_22q2ud {
  fill: currentColor;
  d: path("M14 3a3 3 0 0 1 3 3v6a3 3 0 0 1-2.13 2.871A3 3 0 0 1 12 17H7.5A4.5 4.5 0 0 1 3 12.5V8a3 3 0 0 1 2.129-2.871A3 3 0 0 1 8 3zM5 6.27c-.598.346-1 .99-1 1.73v4.5A3.5 3.5 0 0 0 7.5 16H12c.74 0 1.383-.403 1.729-1H8a3 3 0 0 1-3-3zM8 4a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2zm5.5 2a.5.5 0 0 1 .5.5v4a.5.5 0 0 1-1 0V7.707l-4.146 4.147a.5.5 0 1 1-.708-.707L12.293 7H9.5a.5.5 0 0 1 0-1z");
}

</style>
