<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4pymy1wc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-call-merge" /></template>
<style>
.i4pymy1wc {
  fill: currentColor;
  d: path("M17.7 19.7a.996.996 0 0 0 0-1.41l-2.7-2.7L13.59 17l2.7 2.7c.39.39 1.03.39 1.41 0M8.71 8H11v5.59l-4.71 4.7A.996.996 0 1 0 7.7 19.7l5.3-5.3V8h2.29c.45 0 .67-.54.35-.85l-3.29-3.29c-.2-.2-.51-.2-.71 0L8.35 7.15a.5.5 0 0 0 .36.85");
}

</style>
