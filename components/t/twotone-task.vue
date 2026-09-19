<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xpnxdt7xy"/><path class="qua8wlbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-task" /></template>
<style>
.qua8wlbzm {
  fill: currentColor;
  d: path("M14 2H6c-1.1 0-1.99.9-1.99 2L4 20c0 1.1.89 2 1.99 2H18c1.1 0 2-.9 2-2V8zm4 18H6V4h7v5h5zm-9.18-6.95L7.4 14.46L10.94 18l5.66-5.66l-1.41-1.41l-4.24 4.24z");
}

.xpnxdt7xy {
  fill: currentColor;
  d: path("M13 9V4H6v16h12V9zm-2.06 9L7.4 14.46l1.41-1.41l2.12 2.12l4.24-4.24l1.41 1.41z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
