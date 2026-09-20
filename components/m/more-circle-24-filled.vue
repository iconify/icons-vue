<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-6g7eckt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-circle-24-filled" /></template>
<style>
.z-6g7eckt {
  fill: currentColor;
  d: path("M12 2C6.477 2 2 6.477 2 12s4.477 10 10 10s10-4.477 10-10S17.523 2 12 2M8.25 12a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0m5 0a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0m5 0a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0");
}

</style>
