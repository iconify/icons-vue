<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffnpe-c2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-format-line-spacing" /></template>
<style>
.ffnpe-c2f {
  fill: currentColor;
  d: path("M7.29 7c.45 0 .67-.54.35-.85l-2.29-2.3c-.2-.2-.51-.2-.71 0l-2.29 2.3a.5.5 0 0 0 .36.85H4v10H2.71c-.45 0-.67.54-.35.85l2.29 2.29c.2.2.51.2.71 0l2.29-2.29a.5.5 0 0 0-.36-.85H6V7zM11 7h10c.55 0 1-.45 1-1s-.45-1-1-1H11c-.55 0-1 .45-1 1s.45 1 1 1m10 10H11c-.55 0-1 .45-1 1s.45 1 1 1h10c.55 0 1-.45 1-1s-.45-1-1-1m0-6H11c-.55 0-1 .45-1 1s.45 1 1 1h10c.55 0 1-.45 1-1s-.45-1-1-1");
}

</style>
