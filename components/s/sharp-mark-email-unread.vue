<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uodwnrbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-mark-email-unread" /></template>
<style>
.uodwnrbbx {
  fill: currentColor;
  d: path("M22 8.98V20H2V4h12.1c-.06.32-.1.66-.1 1c0 1.48.65 2.79 1.67 3.71L12 11L4 6v2l8 5l5.3-3.32c.54.2 1.1.32 1.7.32c1.13 0 2.16-.39 3-1.02M16 5c0 1.66 1.34 3 3 3s3-1.34 3-3s-1.34-3-3-3s-3 1.34-3 3");
}

</style>
