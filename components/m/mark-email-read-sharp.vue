<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyehmctwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mark-email-read-sharp" /></template>
<style>
.jyehmctwu {
  fill: currentColor;
  d: path("m15.95 22l-4.25-4.25l1.4-1.4l2.85 2.85l5.65-5.65l1.4 1.4zM2 20V4h20v6.35l-6.025 6.025L13.1 13.5l-4.225 4.225L11.15 20zm10-7l8-5V6l-8 5l-8-5v2z");
}

</style>
