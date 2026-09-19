<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egsxh8ywk"/><path class="c402pbw-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-signal-wifi-4-bar-lock" /></template>
<style>
.c402pbw-o {
  fill: currentColor;
  d: path("M22 16v-1c0-1.1-.9-2-2-2s-2 .9-2 2v1c-.55 0-1 .45-1 1v3c0 .55.45 1 1 1h4c.55 0 1-.45 1-1v-3c0-.55-.45-1-1-1m-1 0h-2v-1c0-.55.45-1 1-1s1 .45 1 1z");
}

.egsxh8ywk {
  fill: currentColor;
  d: path("M21.98 11L24 8.98A16.88 16.88 0 0 0 12 4C7.31 4 3.07 5.9 0 8.98l6.35 6.36L12 21l3.05-3.05V15c0-.45.09-.88.23-1.29c.54-1.57 2.01-2.71 3.77-2.71z");
}

</style>
