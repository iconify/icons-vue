<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dx8wpfzjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mark-email-read-outline" /></template>
<style>
.dx8wpfzjn {
  fill: currentColor;
  d: path("m15.95 22l-4.25-4.25l1.4-1.4l2.85 2.85l5.65-5.65l1.4 1.4zM12 11l8-5H4zm0 2L4 8v10h5.15l2 2H4q-.825 0-1.412-.587T2 18V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v4.35l-2 2V8zm0 0");
}

</style>
