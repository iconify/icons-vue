<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7_nt9j9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-offline-pin" /></template>
<style>
.y7_nt9j9h {
  fill: currentColor;
  d: path("M12 2C6.5 2 2 6.5 2 12s4.5 10 10 10s10-4.5 10-10S17.5 2 12 2m5 16H7v-2h10zm-6.7-4L7 10.7l1.4-1.4l1.9 1.9l5.3-5.3L17 7.3z");
}

</style>
