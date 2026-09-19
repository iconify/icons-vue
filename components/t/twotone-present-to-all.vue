<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9fh_1bmf"/><path class="hj_ly7k3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-present-to-all" /></template>
<style>
.hj_ly7k3s {
  fill: currentColor;
  d: path("M10 16h4v-4h2l-4-4l-4 4h2zM21 3H3c-1.11 0-2 .89-2 2v14c0 1.11.89 2 2 2h18c1.11 0 2-.89 2-2V5c0-1.11-.89-2-2-2m0 16.02H3V4.98h18z");
}

.j9fh_1bmf {
  fill: currentColor;
  d: path("M3 19.02h18V4.98H3zM12 8l4 4h-2v4h-4v-4H8z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
