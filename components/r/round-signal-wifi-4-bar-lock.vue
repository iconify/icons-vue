<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kow7w-ajo"/><path class="c402pbw-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-signal-wifi-4-bar-lock" /></template>
<style>
.c402pbw-o {
  fill: currentColor;
  d: path("M22 16v-1c0-1.1-.9-2-2-2s-2 .9-2 2v1c-.55 0-1 .45-1 1v3c0 .55.45 1 1 1h4c.55 0 1-.45 1-1v-3c0-.55-.45-1-1-1m-1 0h-2v-1c0-.55.45-1 1-1s1 .45 1 1z");
}

.kow7w-ajo {
  fill: currentColor;
  d: path("M23.21 8.24C20.22 5.6 16.3 4 12 4S3.78 5.6.79 8.24C.35 8.63.32 9.3.73 9.71l5.62 5.63l4.94 4.95c.39.39 1.02.39 1.42 0l2.34-2.34V15c0-.45.09-.88.23-1.29c.54-1.57 2.01-2.71 3.77-2.71h2.94l1.29-1.29c.4-.41.37-1.08-.07-1.47");
}

</style>
