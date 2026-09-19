<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="ccvbjb-4z"/><path class="qql_o1-nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-all-out" /></template>
<style>
.ccvbjb-4z {
  cx: 12px;
  cy: 12px;
  r: 5px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

.qql_o1-nn {
  fill: currentColor;
  d: path("M4 4v4l4-4zm12 0l4 4V4zm4 16v-4l-4 4zM4 20h4l-4-4zm15-8c0-3.87-3.13-7-7-7s-7 3.13-7 7s3.13 7 7 7s7-3.13 7-7m-7 5c-2.76 0-5-2.24-5-5s2.24-5 5-5s5 2.24 5 5s-2.24 5-5 5");
}

</style>
