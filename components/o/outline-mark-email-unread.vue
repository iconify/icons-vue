<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyvjyhbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-mark-email-unread" /></template>
<style>
.fyvjyhbof {
  fill: currentColor;
  d: path("M22 8.98V18c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2l.01-12c0-1.1.89-2 1.99-2h10.1c-.06.32-.1.66-.1 1s.04.68.1 1H4l8 5l3.67-2.29c.47.43 1.02.76 1.63.98L12 13L4 8v10h16V9.9c.74-.15 1.42-.48 2-.92M16 5c0 1.66 1.34 3 3 3s3-1.34 3-3s-1.34-3-3-3s-3 1.34-3 3");
}

</style>
