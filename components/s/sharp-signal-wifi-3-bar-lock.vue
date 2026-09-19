<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwoou_bit"/><path class="d40lmhb4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-signal-wifi-3-bar-lock" /></template>
<style>
.d40lmhb4l {
  fill: currentColor;
  d: path("M23 16v-1.34c0-1.47-1.2-2.75-2.66-2.66A2.484 2.484 0 0 0 18 14.5V16h-1v6h7v-6zm-1 0h-3v-1.5c0-.8.7-1.5 1.5-1.5s1.5.7 1.5 1.5zm-6.5-1.5a4.92 4.92 0 0 1 3.27-4.68C17.29 8.98 14.94 8 12 8c-4.81 0-8.04 2.62-8.47 2.95L12 21.5l3.5-4.36z");
}

.dwoou_bit {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M15.5 14.5c0-2.8 2.2-5 5-5c.36 0 .71.04 1.05.11L23.64 7c-.45-.34-4.93-4-11.64-4C5.28 3 .81 6.66.36 7L12 21.5l3.5-4.36z");
}

</style>
