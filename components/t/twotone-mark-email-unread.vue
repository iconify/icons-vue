<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4vby6x_d"/><path class="r9g086brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-mark-email-unread" /></template>
<style>
.h4vby6x_d {
  fill: currentColor;
  d: path("M4 6h10.1c.22 1.07.79 2 1.57 2.71L12 11zm0 2v10h16V9.9a4.84 4.84 0 0 1-2.7-.22L12 13z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.r9g086brg {
  fill: currentColor;
  d: path("M20 9.9c.74-.15 1.42-.48 2-.92V18c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2h10.1c-.06.32-.1.66-.1 1s.04.68.1 1H4l8 5l3.67-2.29c.47.43 1.02.76 1.63.98L12 13L4 8v10h16zM16 5c0 1.66 1.34 3 3 3s3-1.34 3-3s-1.34-3-3-3s-3 1.34-3 3");
}

</style>
